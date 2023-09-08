-- phpMyAdmin SQL Dump
-- version 4.7.7
-- https://www.phpmyadmin.net/
--
-- Хост: localhost
-- Время создания: Мар 04 2019 г., 20:33
-- Версия сервера: 5.7.21-20-beget-5.7.21-20-1-log
-- Версия PHP: 5.6.38

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- База данных: `r95001nb_ferma`
--

-- --------------------------------------------------------

--
-- Структура таблицы `db_bonus_list`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_bonus_list`;
CREATE TABLE `db_bonus_list` (
  `id` int(11) NOT NULL,
  `user` varchar(10) CHARACTER SET utf8 NOT NULL,
  `user_id` int(11) NOT NULL DEFAULT '0',
  `sum` double NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_conabrul`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_conabrul`;
CREATE TABLE `db_conabrul` (
  `id` int(11) NOT NULL,
  `rules` text NOT NULL,
  `about` text NOT NULL,
  `contacts` text NOT NULL
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_conabrul`
--

INSERT INTO `db_conabrul` (`id`, `rules`, `about`, `contacts`) VALUES
(1, '<p><br />&nbsp;1.1. Настоящее Пользовательское соглашение (далее &laquo;Соглашение&raquo;) регламентирует порядок и условия предоставления услуг сайтом <strong>collective-farms.ru,</strong> именуемой далее по тексту &laquo;Организатор&raquo;, и адресовано физическому лицу,  желающему получать услуги указанного сайта (далее &laquo;Участник&raquo;.)&nbsp;<br /><br /> 1.2. Для начала получения услуг участник явно, полно и безоговорочно  принимает все условия настоящего Соглашения, и, если Вы не согласны с  каким-либо условием соглашения, Организатор предлагает Вам отказаться от  использования его услуг. <br /><br /> 1.3. Организатор и участник признают  порядок и форму заключения настоящего соглашения равнозначным по  юридической силе соглашению, заключенному в письменной форме. <br /><br /> <strong>Термины и Определения. </strong><br /><br /> 2.1 Игра &mdash; вид деятельности, направленный на удовлетворение  потребностей человека в развлечении, удовольствии, снятию напряжения, а  также на развитие определенных навыков и умений в форме свободного  самовыражения человека, не связанных с достижением утилитарных целей и  доставляющих радость сами по себе. <br /><br /> 2.2 Игровая площадка &mdash;  программно-аппаратный комплекс физических устройств и программного  обеспечения, расположенный в глобальной сети Интернет, предназначенный  для организации проведения досуга и отдыха. <br /><br />&nbsp;2.3 Игра &laquo; <strong>collective-farms.ru</strong> &raquo;, экономическая онлайн-игра &laquo;Игра колхох&raquo; - обособленное и  уникальное название игровой площадки, принадлежащей организатору и  находящейся по адресам в сети интернет <strong>collective-farms.ru</strong> , на  которой Организатором предоставляются услуги участнику по организации  его развлечения, досуга и отдыха в порядке и на условиях, изложенных в  настоящем соглашении.&nbsp;<br /><br />&nbsp;2.4 Игровой инвентарь &mdash; условная игровая  единица для участия в игре, именуемая серебро, местом учета и хранения,  которой является игровой счет участника в электронном виде в формате  учетной записи в системе игровой площадки &laquo; <strong>collective-farms.ru</strong> &raquo;.&nbsp;<br /><br /> 2.5 Игровой счет &mdash; виртуальный счет участника игры, предоставляемый  организатором каждому участнику на игровой площадке для учета игрового  инвентаря - серебро. <br /><br /> <strong>Предмет соглашения. </strong><br /><br />&nbsp;3.1.  Предметом настоящего Соглашения является предоставление организатором  участнику услуг по организации досуга и отдыха в игре &laquo; <strong>collective-farms.ru</strong>&raquo; в соответствии с условиями настоящего Соглашения.&nbsp;<br /><br /> 3.2. Под такими услугами (п.3.1), в частности, понимаются следующие:  услуги по покупке-продаже игрового инвентаря, ведение учета значимой  информации: движения по игровому счету, обеспечение мер по идентификации  и безопасности участников, разработка программного обеспечения,  интегрируемого в игровую площадку и внешние приложения, информационные и  другие услуги, необходимые для организации игры и обслуживания  участника в ее процессе на площадке организатора. <br /><br /> 3.3. Игра в  целом, а равно любой ее элемент или любое сопряженное внешнее игровое  приложение, созданы исключительно для развлечений. Участник признает,  что все виды деятельности в игре на игровой площадке являются для него  развлечением. Участник соглашается с тем, что в зависимости от  характеристик его аккаунта, степень его участия в игре будет доступна в  различной мере. <br /><br /> 3.4. Участник соглашается, что он несет  персональную ответственность за все действия, произведенные с игровым  инвентарем: покупкой, продажей, вводом и выводом, а также за игровые  действия на игровой площадке: создание, покупку-продажу, операции со  всеми игровыми элементами и другими игровыми атрибутами и объектами,  используемыми для игрового процесса. <br /><br /> 3.5. Участник признает,  что степень и возможность участия в развлечениях на сервере Игры  являются главными качествами оказываемой ему услуги. <br /><br /> <strong>Права и обязанности сторон. </strong><br /><br /> <em>Права и обязанности участника: </em><br /><br />&nbsp;4.1.1.  Принимать участие в игре &laquo; <strong>collective-farms.ru</strong> &raquo; могут только лица, достигшие  гражданской дееспособности по законодательству страны своей резиденции.  Все последствия неисполнения данного условия возлагаются на участника.&nbsp;<br /><br /> 4.1.2. Степень и способ участия в игре определяются самим участником,  но не могут противоречить настоящему Соглашению и правилам игровой  площадки. <br /><br /> <em>Участник обязан: </em><br /><br /> 4.1.2.1. правдиво  сообщать сведения о себе при регистрации и по первому требованию  Организатора предоставить достоверные данные о своей личности,  позволяющие идентифицировать его как владельца аккаунта в игре; <br /><br /> 4.1.2.2. не использовать игру для совершения каких-либо действий,  противоречащих международному законодательству и законодательству страны  &mdash; резиденции Участника; <br /><br /> 4.1.2.3. не использовать  недокументированные особенности (баги) и ошибки программного обеспечения  игры и незамедлительно сообщать Организатору о них, а так же о лицах,  использующих эти ошибки; <br /><br /> 4.1.2.4. не использовать внешние программы любого рода, для получения преимуществ в игре; <br /><br /> 4.1.2.5. не использовать для рекламы своей партнерской ссылки, а равно  ресурса, ее содержащего, почтовые рассылки и иного вида сообщения лицам,  не выражавшим согласия их получать (спам); <br /><br /> 4.1.2.6. не вправе  ограничивать доступ других участников или других лиц к Игре, обязан  уважительно и корректно относиться к участникам игры, а так же к  Организатору, его партнерам и сотрудникам, не создавать помехи в работе  последних; <br /><br /> 4.1.2.7. не обманывать Организатора и участников игры; <br /><br /> 4.1.2.8. не использовать ненормативную лексику и оскорбления в любой форме; <br /><br /> 4.1.2.9. не порочить действия других игроков и Администрации; <br /><br /> 4.1.2.10. не угрожать насилием и физической расправой кому бы то ни было; <br /><br /> 4.1.2.11. не распространять материалы пропагандирующие неприятие или  ненависть к любой расе, религии, культуре, нации, народу, языку,  политике, государству, идеологии или общественному движению; <br /><br /> 4.1.2.12. не рекламировать порнографию, наркотики и ресурсы, содержащие подобную информацию; <br /><br /> 4.1.2.13. не использовать действия, терминологию или жаргон для завуалирования нарушения обязанностей участника; <br /><br /> 4.1.2.14. самостоятельно заботиться о необходимых мерах компьютерной и  иной безопасности, хранить в секрете и не передавать другому лицу или  другому участнику свои идентификационные данные: логин, пароль аккаунта и  др., не допускать несанкционированного доступа к почтовому ящику,  указанному в профиле аккаунта участника. Весь риск неблагоприятных  последствий разглашения этих данных несет участник, так как участник  согласен с тем, что система информационной безопасности игровой площадки  исключает передачу логина, пароля и идентификационной информации  аккаунта участника третьим лицам; <br /><br /> 4.1.2.15. самостоятельно  нести персональную ответственность за ведение своих финансовых сделок и  операций, Организатор не несет ответственности за совершаемые финансовые  действия между игроками по передаче игрового инвентаря и игровой  валюты, а равно иных игровых атрибутов. <br /><br /> 4.1.2.16. о своих претензиях и жалобах первым уведомлять организатора в письменной форме через страницу &laquo;Контакты&raquo;. <br /><br /> 4.1.2.17. регулярно самостоятельно знакомиться с новостями игры, а  также с изменениями в настоящем Соглашении и в правилах игры на игровой  площадке.<br /><br />4.1.2.18. запрещено регистрировать более одного  аккаунта в игре, если один аккаунт является рефералом другого, с целью  получения реферальских отчислений. Такие регистрации участников будут  заблокированны.<br /><br /> <strong>Права и обязанности организатора. <br /></strong> 4.2.1. Организатор обязан: <br /><br /> 4.2.1.1. обеспечить без взимания платы доступ участника на игровую  площадку и к участию в игре. Участник самостоятельно за свой счет  оплачивает доступ в сеть Интернет и несет иные расходы, связанные с  данным действием. <br /><br /> 4.2.1.2. вести учет игрового инвентаря на игровом счете участника. <br /><br /> 4.2.1.3. регулярно совершенствовать аппаратно-программный комплекс, но  не гарантирует, что программное обеспечение Игры не содержит ошибок, а  аппаратная часть не выйдет из рабочих параметров и будет функционировать  бесперебойно. <br /><br /> 4.2.1.4. Соблюдать режим конфиденциальности в отношении персональных данных участника в порядке п.6 настоящего соглашения. <br /><br /> 4.2.1.5. Нести финансовые обязательства по обеспечению эквивалентной  курсовой стоимости игрового инвентаря на игровом счете участника.  Курсовая стоимость игрового инвентаря равняется: 100 Серебра = 1 рубль  российской федерации. <br /><br /> 4.2.1.6. Любому лицу, законно владеющему  игровым инвентарем, гарантируется оплата денежной суммы, обусловленной  курсовой стоимостью серебра, за вычетом затрат на осуществление данной  операции. изменять курс игрового инвентаря <br /><br /> 4.2.2. <em>Организатор имеет право: </em></p>\r\n<p><em><br /></em> 4.2.2.2. предоставлять участнику дополнительные платные  услуги, перечень которых, а также порядок и условия пользования  которыми определяются настоящим соглашением, правилами игровой площадки и  иными объявлениями организатора. При этом организатор вправе в любое  время изменить количество и объем предлагаемых платных услуг, их  стоимость, название, вид и эффект от использования. <br /><br /> 4.2.2.3.  приостановить действие настоящего соглашения и отключить участника от  участия в игре на время проведения расследования по подозрению участника  в нарушении настоящего Соглашения и правил игровой площадки. <br /><br /> 4.2.2.4. исключить участника из игры, если установит, что участник  нарушил настоящее соглашение или правила, установленные на игровой  площадке, в порядке 5.10 настоящего соглашения. <br /><br /> 4.2.2.5.  частично или полностью прерывать предоставление услуг без предупреждения  участника при проведении реконструкции, ремонта и профилактических  работ на площадке. <br /><br /> 4.2.2.6. Организатор не несет  ответственности за неправильное функционирование программного  обеспечения игры. Участник использует программное обеспечение по  принципу &laquo;КАК ЕСТЬ&raquo; (&ldquo;AS IS&rdquo;). Если организатор установит, что при игре  возник сбой (ошибка) в работе площадки, то результаты, которые  состо4308,5_349566118560,EE время некорректной работы программного  обеспечения, могут быть аннулированы или скорректированы по усмотрению  организатора. Участник согласен не апеллировать к организатору по поводу  качества, количества, порядка и сроков предоставляемых ему игровых  возможностей и услуг. <br /><br /> 4.2.2.7. в одностороннем порядке изменять курс игрового инвентаря.<br /><br /><strong>Гарантии и ответственность. </strong></p>\r\n<p><strong><br /></strong> 5.1. Организатор не гарантирует постоянный и  непрерывный доступ к игровой площадке и его услугам в случае  возникновения технических неполадок и/или непредвиденных обстоятельств, в  числе которых: неполноценная работа или не функционирование  интернет&ndash;провайдеров, серверов информации, банковских и платёжных  систем, а также неправомерных действий третьих лиц. Организатор приложит  все усилия по недопущению сбоев, но не несет ответственности за  временные технические сбои и перерывы в работе Игры, вне зависимости от  причин таких сбоев. <br /><br /> 5.2 Участник полностью согласен, что  организатор не может нести ответственность за убытки участника, которые  возникли в связи с противоправными действиями третьих лиц, направленными  на нарушение системы безопасности электронного оборудования и баз  данных игры, либо вследствие независящих от организатора перебоев,  приостановления или прекращения работы каналов и сетей связи,  используемых для взаимодействия с участником, а также неправомерных или  необоснованных действий платежных систем, а так же третьих лиц. <br /><br /> 5.3. Организатор не несет ответственности за убытки, понесенные в  результате использования или не использования участником информации об  Игре, игровых правил и самой Игры и не несет ответственности за убытки  или иной вред, возникший у участника в связи с его неквалифицированными  действиями и незнанием игровых правил или его ошибках в расчетах; <br /><br /> 5.4. Участник согласен с тем, что использует игровую площадку по своей  доброй воле и на свой собственный риск. Организатор не дает участнику  никакой гарантии того, что он извлечет выгоду или пользу от участия в  игре. Степень участия в Игре определяется самим участником. <br /><br /> 5.5. Организатор не несет ответственности перед участником за действия других участников. <br /><br /> 5.6. В случае возникновения споров и разногласий на игровой площадке,  решение организатора является окончательным, и участник с ним полностью  согласен. Все споры и разногласия, возникающие из настоящего Соглашения  или в связи с ним, подлежат разрешению путем переговоров. В случае  невозможности достижения согласия путем переговоров, споры, разногласия и  требования, возникающие из настоящего Соглашения, подлежат разрешению в  соответствии с действующим законодательством государтсва Белиз. <br /><br /> 5.7. Организатор не несет налогового бремени за Участника. Участник  обязуется самостоятельно включать возможные полученные доходы в  налоговую декларацию в соответствии с законодательством страны своей  резиденции. <br /><br /> 5.8. Организатор может вносить изменения в  настоящее Соглашение, правила игровой площадки и другие документы в  одностороннем порядке. В случае внесения изменений в документы  Организатор размещает последние версии документов на сайте игровой  площадки. Все изменения вступают в силу с момента размещения. Участник  имеет право расторгнуть настоящее Соглашение в течение 3 дней, если он  не согласен с внесенными изменениями. В таком случае расторжение  Соглашения производится согласно п. 5.9 настоящего Соглашения. На  Участника возлагается обязанность регулярно посещать официальный сайт  Игры с целью ознакомления с официальными документами и новостями. <br /><br /> 5.9. Участник имеет право расторгнуть настоящее Соглашение в  одностороннем порядке без сохранения игрового аккаунта. При этом все  расходы, связанные с участием в игре, участнику не компенсируются и не  возвращаются. Игровой инвентарь, который был на игровом счете участника,  подлежат возврату в порядке п. 4.2.1.6 настоящего Соглашения. <br /><br /> 5.10. Организатор имеет право расторгнуть настоящее Соглашение в  одностороннем порядке, а также совершать иные действия, ограничивающие  возможности в Игре, в отношении участника или группы участников,  являющихся соучастниками выявленных нарушений условий настоящего  Соглашения. При этом все игровые атрибуты, игровой инвентарь находящиеся  в аккаунте и на игровом счете участника или группы участников, а равно  все расходы возврату не подлежат и не компенсируются. <br /><br /> 5.11. Организатор и Участник несут ответственность за неисполнение или <br /><br /><strong>Конфиденциальность.</strong> <br /><br /> 6.1. Условие конфиденциальности распространяется на информацию, которую  Организатор может получить об Участнике во время его пребывания на  сайте Игры и которая может быть соотнесена с данным конкретным  пользователем. Организатор автоматически получает и записывает в  серверные логи техническую информацию из вашего браузера: IP адрес,  адрес запрашиваемой страницы и т.д. Организатор может записывать  &laquo;cookies&raquo; на компьютер пользователя и впоследствии использовать их.  Организатор гарантирует, что данные, сообщенные участником при  регистрации в Игре, будут использоваться Организатором только внутри  Игры. <br /><br /> 6.2. Организатор вправе передать персональную информацию об Участнике третьим лицам только в случаях, если: <br /><br /> 6.2.1. Участник изъявил желание раскрыть эту информацию; <br /><br /> 6.2.2. Без этого Участник не может воспользоваться желаемым продуктом  или услугой, в частности - информация об именах (никах), игровых  атрибутах - может быть доступна другим участникам; <br /><br /> 6.2.3. Этого требует международное законодательство и/или органы власти с соблюдением законной процедуры; <br /><br /> 6.2.4. Участник нарушает настоящее Cоглашение и правила игровой площадки. <br /><br /> <strong>Иные положения. </strong><br /><br /> 7.1. Недействительность части или пункта (подпункта) настоящего  соглашения не влечет недействительности всех остальных частей и пунктов  (подпунктов). <br /><br /> 7.2. Срок действия настоящего Соглашения  устанавливается на весь период действия игровой площадки, то есть на  неопределенный срок, и не предполагает срока окончания данного  соглашения. <br /><br /> 7.3. Регистрируясь и находясь на игровой площадке,  участник признает, что он прочитал, понял и полностью принимает условия  настоящего Соглашения, а также правила игры и иных официальных  документов. <br /><br /> 7.4. Соглашение вступает в силу с момента регистрации участника в проекте. <br /><br /><em><strong>&nbsp;Организатор Проект: </strong></em><strong>collective-farms.ru</strong></p>', '<p><span style=\"color: #008000;\"><strong>Автоматическая система накопления продукции! Сбор продукции без  потерь, без ограничений по срокам! Собирайте продукйию, так как удобно  именно Вам -&nbsp;</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Хоть раз в час, хоть раз в день, хоть раз в месяц! Продукция никогда не испортится и не пропадет!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Системный рынок позволит мгновенно обменять продукцию на Серебро! <br /></strong></span></p>\r\n<p><span style=\"color: #008000;\"><strong>Вам даже не нужно звать людей в игру для того, чтобы получить прибыль, система всё делает сама! </strong></span><br /><br /><span style=\"color: #008000;\"><strong>Максимально быстрые выплаты денег на Ваш кошелек! Любую сумму от 0.50 руб.! Без дополнительных лимитов и ограничений!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>В игре всегда можно посмотреть системный резервный фонд на выкуп урожая! Он отображается в реальном времени и Вы всегда в курсе!</strong></span></p>\r\n<p><span style=\"color: #008000;\"><strong><br />Резерв системы на выкуп продукции гарантирует пользователям автоматический выкуп продукции и получение стабильного дохода. </strong></span><br /><br /><span style=\"color: #008000;\"><strong>Резерв  системы показывается и обновляется в онлайн режиме. Администрация  проекта гарантирует выкуп продукции на сумму, которая есть в резерве!</strong> </span><br /><br /><span style=\"color: #008000;\"><strong>Резерв системы - это гарант, который Администрация обязуется выплачивать!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Каждый пользователь стабильно будет получать доход.</strong></span></p>\r\n<p><br /><span style=\"color: #008000;\"><strong>В процессе игры дополнительно будут добавлены новые блоки, которые позволят стабильно пополнять резерв на выкуп урожая!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Также  при большом сборе средств в резерве на выкуп продукцити, администрация  проекта планирует инвестиции для получения дохода, который будет  пополнять резерв системы на выкуп!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Ваш колхоз будет приносить прибыль всегда!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>И даже, если резерв системы опустошится и станет равен нулю Вы всё равно будете продолжать стабильно получать доход!</strong></span><br /><br /><span style=\"color: #008000;\"><strong>Продукция будет накапливаться дальше и Вы будете получать серебро, просто заявки  на продажу продукции будут формироваться в виде очереди!</strong></span></p>\r\n<p><span style=\"color: #008000;\"><strong><br />Стабильный прирост резерва всегда будет обеспечивать все  выплаты, а далее и очередь обмена продукции, которые будут обрабатываться  по очереди!</strong>&nbsp;</span><br /><br /><span style=\"color: #008000;\"><strong>&nbsp;Проект</strong>:&nbsp;<em>&laquo;</em>collective-farms.ru<em>&raquo;.</em></span></p>', '<p><em><strong>Если у вас возникли вопросы, предложения или жалобы. Обращайтесь на почту <span style=\"color: #ff0000;\">spirit1@bigmir.net</span></strong></em></p>');

-- --------------------------------------------------------

--
-- Структура таблицы `db_config`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_config`;
CREATE TABLE `db_config` (
  `id` int(11) NOT NULL,
  `admin` varchar(10) NOT NULL,
  `pass` varchar(20) NOT NULL,
  `min_pay` double NOT NULL DEFAULT '15',
  `ser_per_wmr` int(11) NOT NULL DEFAULT '1000',
  `ser_per_wmz` int(11) NOT NULL DEFAULT '3300',
  `ser_per_wme` int(11) NOT NULL DEFAULT '4200',
  `percent_swap` int(11) NOT NULL DEFAULT '0',
  `percent_sell` int(2) NOT NULL DEFAULT '10',
  `items_per_coin` int(11) NOT NULL DEFAULT '7',
  `a_in_h` int(11) NOT NULL DEFAULT '0',
  `b_in_h` int(11) NOT NULL DEFAULT '0',
  `c_in_h` int(11) NOT NULL DEFAULT '0',
  `d_in_h` int(11) NOT NULL DEFAULT '0',
  `e_in_h` int(11) NOT NULL DEFAULT '0',
  `amount_a_t` int(11) NOT NULL DEFAULT '0',
  `amount_b_t` int(11) NOT NULL DEFAULT '0',
  `amount_c_t` int(11) NOT NULL DEFAULT '0',
  `amount_d_t` int(11) NOT NULL DEFAULT '0',
  `amount_e_t` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_config`
--

INSERT INTO `db_config` (`id`, `admin`, `pass`, `min_pay`, `ser_per_wmr`, `ser_per_wmz`, `ser_per_wme`, `percent_swap`, `percent_sell`, `items_per_coin`, `a_in_h`, `b_in_h`, `c_in_h`, `d_in_h`, `e_in_h`, `amount_a_t`, `amount_b_t`, `amount_c_t`, `amount_d_t`, `amount_e_t`) VALUES
(1, 'admin', 'admin', 20, 100, 3300, 4200, 50, 40, 100, 100, 205, 420, 860, 1800, 500, 1000, 2000, 3000, 4000);

-- --------------------------------------------------------

--
-- Структура таблицы `db_games_knb`
--
-- Создание: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_games_knb`;
CREATE TABLE `db_games_knb` (
  `id` int(11) NOT NULL,
  `summa` decimal(7,2) NOT NULL,
  `item` int(1) NOT NULL,
  `login` varchar(10) NOT NULL,
  `dat` datetime NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

-- --------------------------------------------------------

--
-- Структура таблицы `db_insert_money`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_insert_money`;
CREATE TABLE `db_insert_money` (
  `id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `user_id` int(11) NOT NULL DEFAULT '0',
  `money` double NOT NULL DEFAULT '0',
  `serebro` int(11) NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_insert_money`
--

INSERT INTO `db_insert_money` (`id`, `user`, `user_id`, `money`, `serebro`, `date_add`, `date_del`) VALUES
(1, 'kocmo12', 1, 0.1, 11, 1377854769, 1379150769),
(2, 'kocmo12', 1, 1, 100, 1377855416, 1379151416);

-- --------------------------------------------------------

--
-- Структура таблицы `db_lottery`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_lottery`;
CREATE TABLE `db_lottery` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL DEFAULT '0',
  `user` varchar(10) NOT NULL,
  `date_add` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_lottery_winners`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_lottery_winners`;
CREATE TABLE `db_lottery_winners` (
  `id` int(11) NOT NULL,
  `user_a` varchar(10) NOT NULL,
  `bil_a` int(11) NOT NULL DEFAULT '0',
  `user_b` varchar(10) NOT NULL,
  `bil_b` int(11) NOT NULL DEFAULT '0',
  `user_c` varchar(10) NOT NULL,
  `bil_c` int(11) NOT NULL DEFAULT '0',
  `bank` float NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_news`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_news`;
CREATE TABLE `db_news` (
  `id` int(11) NOT NULL,
  `title` varchar(100) NOT NULL,
  `news` text NOT NULL,
  `date_add` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_payeer_insert`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_payeer_insert`;
CREATE TABLE `db_payeer_insert` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `sum` double NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `status` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_payeer_insert`
--

INSERT INTO `db_payeer_insert` (`id`, `user_id`, `user`, `sum`, `date_add`, `status`) VALUES
(1, 1, 'kocmo12', 0.1, 1377854691, 1),
(2, 1, 'kocmo12', 1, 1377855255, 1);

-- --------------------------------------------------------

--
-- Структура таблицы `db_payment`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_payment`;
CREATE TABLE `db_payment` (
  `id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `user_id` int(11) NOT NULL,
  `purse` varchar(20) NOT NULL,
  `sum` double NOT NULL DEFAULT '0',
  `comission` double NOT NULL DEFAULT '0',
  `valuta` varchar(3) NOT NULL DEFAULT 'RUB',
  `serebro` int(11) NOT NULL DEFAULT '0',
  `status` int(11) NOT NULL DEFAULT '0',
  `pay_sys` varchar(100) NOT NULL DEFAULT '0',
  `pay_sys_id` int(11) NOT NULL DEFAULT '0',
  `response` int(1) NOT NULL DEFAULT '0',
  `payment_id` int(11) NOT NULL,
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_payment`
--

INSERT INTO `db_payment` (`id`, `user`, `user_id`, `purse`, `sum`, `comission`, `valuta`, `serebro`, `status`, `pay_sys`, `pay_sys_id`, `response`, `payment_id`, `date_add`, `date_del`) VALUES
(1, 'kocmo12', 1, 'P1736392', 0.5, 0, 'RUB', 50, 3, '0', 0, 0, 1448724, 1377855693, 0);

-- --------------------------------------------------------

--
-- Структура таблицы `db_recovery`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_recovery`;
CREATE TABLE `db_recovery` (
  `id` int(11) NOT NULL,
  `email` varchar(50) NOT NULL,
  `ip` int(10) UNSIGNED NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_regkey`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 18:44
--

DROP TABLE IF EXISTS `db_regkey`;
CREATE TABLE `db_regkey` (
  `id` int(11) NOT NULL,
  `email` varchar(50) NOT NULL,
  `referer_id` int(11) NOT NULL DEFAULT '0',
  `referer_name` varchar(10) NOT NULL,
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_regkey`
--

INSERT INTO `db_regkey` (`id`, `email`, `referer_id`, `referer_name`, `date_add`, `date_del`) VALUES
(9, 'grigor7979@mail.ru', 1, 'First', 1551638647, 1551642247);

-- --------------------------------------------------------

--
-- Структура таблицы `db_sell_items`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 21:28
--

DROP TABLE IF EXISTS `db_sell_items`;
CREATE TABLE `db_sell_items` (
  `id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `user_id` int(11) NOT NULL,
  `a_s` int(11) NOT NULL DEFAULT '0',
  `b_s` int(11) NOT NULL DEFAULT '0',
  `c_s` int(11) NOT NULL DEFAULT '0',
  `d_s` int(11) NOT NULL DEFAULT '0',
  `e_s` int(11) NOT NULL DEFAULT '0',
  `amount` double NOT NULL DEFAULT '0',
  `all_sell` int(11) NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_sell_items`
--

INSERT INTO `db_sell_items` (`id`, `user`, `user_id`, `a_s`, `b_s`, `c_s`, `d_s`, `e_s`, `amount`, `all_sell`, `date_add`, `date_del`) VALUES
(1, 'kocmo12', 1, 4827586, 0, 0, 0, 0, 48275.86, 4827586, 1551648514, 1552944514);

-- --------------------------------------------------------

--
-- Структура таблицы `db_sender`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_sender`;
CREATE TABLE `db_sender` (
  `id` int(11) NOT NULL,
  `name` varchar(255) NOT NULL,
  `mess` text NOT NULL,
  `page` int(5) NOT NULL DEFAULT '0',
  `sended` int(7) NOT NULL DEFAULT '0',
  `status` int(1) NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_stats`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_stats`;
CREATE TABLE `db_stats` (
  `id` int(11) NOT NULL,
  `all_users` int(11) NOT NULL DEFAULT '0',
  `all_payments` double NOT NULL DEFAULT '0',
  `all_insert` double NOT NULL DEFAULT '0',
  `donations` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_stats_btree`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_stats_btree`;
CREATE TABLE `db_stats_btree` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL DEFAULT '0',
  `user` varchar(10) NOT NULL,
  `tree_name` varchar(10) NOT NULL,
  `amount` double NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_swap_ser`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 17:10
--

DROP TABLE IF EXISTS `db_swap_ser`;
CREATE TABLE `db_swap_ser` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `amount_b` double NOT NULL DEFAULT '0',
  `amount_p` double NOT NULL DEFAULT '0',
  `date_add` int(11) NOT NULL DEFAULT '0',
  `date_del` int(11) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

-- --------------------------------------------------------

--
-- Структура таблицы `db_users_a`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 04 2019 г., 17:22
--

DROP TABLE IF EXISTS `db_users_a`;
CREATE TABLE `db_users_a` (
  `id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `email` varchar(50) NOT NULL,
  `pass` varchar(20) NOT NULL,
  `referer` varchar(10) NOT NULL,
  `referer_id` int(11) NOT NULL DEFAULT '0',
  `referals` int(11) NOT NULL DEFAULT '0',
  `date_reg` int(11) NOT NULL DEFAULT '0',
  `date_login` int(11) NOT NULL DEFAULT '0',
  `ip` int(10) UNSIGNED NOT NULL DEFAULT '0',
  `banned` int(1) NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_users_a`
--

INSERT INTO `db_users_a` (`id`, `user`, `email`, `pass`, `referer`, `referer_id`, `referals`, `date_reg`, `date_login`, `ip`, `banned`) VALUES
(1, 'kocmo12', 'big-babku@yandex.ru', '123123', 'First', 1, 1, 1377854669, 1551720166, 1551048623, 0);

-- --------------------------------------------------------

--
-- Структура таблицы `db_users_b`
--
-- Создание: Мар 03 2019 г., 17:10
-- Последнее обновление: Мар 03 2019 г., 21:28
--

DROP TABLE IF EXISTS `db_users_b`;
CREATE TABLE `db_users_b` (
  `id` int(11) NOT NULL,
  `user` varchar(10) NOT NULL,
  `money_b` double NOT NULL DEFAULT '0',
  `money_p` double NOT NULL DEFAULT '0',
  `a_t` int(11) NOT NULL DEFAULT '0',
  `b_t` int(11) NOT NULL DEFAULT '0',
  `c_t` int(11) NOT NULL DEFAULT '0',
  `d_t` int(11) NOT NULL DEFAULT '0',
  `e_t` int(11) NOT NULL DEFAULT '0',
  `a_b` int(11) NOT NULL DEFAULT '0',
  `b_b` int(11) NOT NULL DEFAULT '0',
  `c_b` int(11) NOT NULL DEFAULT '0',
  `d_b` int(11) NOT NULL DEFAULT '0',
  `e_b` int(11) NOT NULL DEFAULT '0',
  `all_time_a` int(11) NOT NULL DEFAULT '0',
  `all_time_b` int(11) NOT NULL DEFAULT '0',
  `all_time_c` int(11) NOT NULL DEFAULT '0',
  `all_time_d` int(11) NOT NULL DEFAULT '0',
  `all_time_e` int(11) NOT NULL DEFAULT '0',
  `last_sbor` int(11) NOT NULL DEFAULT '0',
  `from_referals` double NOT NULL DEFAULT '0',
  `to_referer` double NOT NULL DEFAULT '0',
  `payment_sum` double NOT NULL DEFAULT '0',
  `insert_sum` double NOT NULL DEFAULT '0'
) ENGINE=MyISAM DEFAULT CHARSET=cp1251;

--
-- Дамп данных таблицы `db_users_b`
--

INSERT INTO `db_users_b` (`id`, `user`, `money_b`, `money_p`, `a_t`, `b_t`, `c_t`, `d_t`, `e_t`, `a_b`, `b_b`, `c_b`, `d_b`, `e_b`, `all_time_a`, `all_time_b`, `all_time_c`, `all_time_d`, `all_time_e`, `last_sbor`, `from_referals`, `to_referer`, `payment_sum`, `insert_sum`) VALUES
(1, 'kocmo12', 29087.615999999998, 20260.344, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4827586, 0, 0, 0, 0, 1551648508, 11.1, 11.1, 0.5, 1.1);

--
-- Индексы сохранённых таблиц
--

--
-- Индексы таблицы `db_bonus_list`
--
ALTER TABLE `db_bonus_list`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_conabrul`
--
ALTER TABLE `db_conabrul`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_config`
--
ALTER TABLE `db_config`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_games_knb`
--
ALTER TABLE `db_games_knb`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_insert_money`
--
ALTER TABLE `db_insert_money`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_lottery`
--
ALTER TABLE `db_lottery`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_lottery_winners`
--
ALTER TABLE `db_lottery_winners`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_news`
--
ALTER TABLE `db_news`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_payeer_insert`
--
ALTER TABLE `db_payeer_insert`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_payment`
--
ALTER TABLE `db_payment`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_recovery`
--
ALTER TABLE `db_recovery`
  ADD PRIMARY KEY (`id`),
  ADD KEY `ip` (`ip`);

--
-- Индексы таблицы `db_regkey`
--
ALTER TABLE `db_regkey`
  ADD PRIMARY KEY (`id`),
  ADD UNIQUE KEY `email` (`email`);

--
-- Индексы таблицы `db_sell_items`
--
ALTER TABLE `db_sell_items`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_sender`
--
ALTER TABLE `db_sender`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_stats`
--
ALTER TABLE `db_stats`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_stats_btree`
--
ALTER TABLE `db_stats_btree`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_swap_ser`
--
ALTER TABLE `db_swap_ser`
  ADD PRIMARY KEY (`id`);

--
-- Индексы таблицы `db_users_a`
--
ALTER TABLE `db_users_a`
  ADD PRIMARY KEY (`id`),
  ADD UNIQUE KEY `email` (`email`),
  ADD KEY `ip` (`ip`);

--
-- Индексы таблицы `db_users_b`
--
ALTER TABLE `db_users_b`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT для сохранённых таблиц
--

--
-- AUTO_INCREMENT для таблицы `db_bonus_list`
--
ALTER TABLE `db_bonus_list`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_conabrul`
--
ALTER TABLE `db_conabrul`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;

--
-- AUTO_INCREMENT для таблицы `db_config`
--
ALTER TABLE `db_config`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;

--
-- AUTO_INCREMENT для таблицы `db_games_knb`
--
ALTER TABLE `db_games_knb`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_insert_money`
--
ALTER TABLE `db_insert_money`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=3;

--
-- AUTO_INCREMENT для таблицы `db_lottery`
--
ALTER TABLE `db_lottery`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_lottery_winners`
--
ALTER TABLE `db_lottery_winners`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_news`
--
ALTER TABLE `db_news`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_payeer_insert`
--
ALTER TABLE `db_payeer_insert`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=3;

--
-- AUTO_INCREMENT для таблицы `db_payment`
--
ALTER TABLE `db_payment`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;

--
-- AUTO_INCREMENT для таблицы `db_recovery`
--
ALTER TABLE `db_recovery`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_regkey`
--
ALTER TABLE `db_regkey`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=10;

--
-- AUTO_INCREMENT для таблицы `db_sell_items`
--
ALTER TABLE `db_sell_items`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;

--
-- AUTO_INCREMENT для таблицы `db_sender`
--
ALTER TABLE `db_sender`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_stats`
--
ALTER TABLE `db_stats`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_stats_btree`
--
ALTER TABLE `db_stats_btree`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_swap_ser`
--
ALTER TABLE `db_swap_ser`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;

--
-- AUTO_INCREMENT для таблицы `db_users_a`
--
ALTER TABLE `db_users_a`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;# Blog
