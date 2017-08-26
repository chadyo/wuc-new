---
layout: post
title: Что такое биткойн майнинг?
description: Что такое биткойн майнинг?
author: Melvin Draupnir
author-url: /melvin-draupnir/
published: true
---

<center><iframe width="700" height="394" src="https://www.youtube.com/embed/GmOzih6I1zs" frameborder="0" allowfullscreen></iframe></center>

<h2>Прежде чем начать ...</h2>
 
Прежде чем продолжить чтение, пожалуйста, примите во внимание, что большинство пользователей биткойнов не занимаются майнингом! Но если вы занимаетесь этим, то данный биткойн майнер возможно является наилучшей сделкой. Биткойн майнинг для получения прибыли имеет жесткую конкуренцию, а нестабильность в цене биткойна затрудняет реализацию денежной прибыли без спекуляции ее цены. Майнинг (добыча) приобретает смысл в случае если вы планируете заниматься этим ради удовольствия, либо его изучения или для поддержки безопасности биткойна, и не обращаете особое внимание на получение прибыли. Если у вас есть доступ к большому объему дешевой электроэнергии, и вы в состоянии управлять большой установкой и делом, то вы можете добывать ради прибыли.

Если вы хотите добывать биткойны на основе фиксированного объема мощности для майнинга, но при этом не хотите управлять оборудованием сами, вы можете приобрести майнинг договор.

Еще один инструмент, покупаемый многими людьми - это биткойновая дебетовая карта, позволяющая загружать дебетовую карту средствами через биткойны.

<h2>Что такое биткойн майнинг?</h2>

Биткойн майнинг во многом похож на гигантскую лотерею, где вы, чтобы заработать биткойны, конкурируете с помощью майнинг-оборудования с другими пользователями сети. Более шустрое биткойн-оборудование для майнинга в состоянии делать большее количество попыток в секунду чтобы выиграть в данной лотерее, в то время как сеть биткойн самонастраивается примерно каждые две недели для поддержки скорости поиска выигрышного блочного хеша каждые десять минут. По большому счету, биткойн майнинг обеспечивает безопасность транзакций, записываемых в публичной книге биткойн, известной как блокчейн. Играя в выборочную лотерею, в которой электричество и специальное оборудование является ценой допуска к игре, затраты на выведение из строя сеть биткойн соизмеряются объемом мощности хеширования, которая тратится всеми майнерами.

<h2>Технические предпосылки</h2>

Во время добычи ваше оборудование для биткойн майнинга оперирует функцией криптографического хеширования (два круга SHA256) на так называемой блочной головке. Для каждого нового испытываемого хеша, программное обеспечение для майнинга будет использовать разное число в виде случайного элемента блочной головки, этот номер называется одноразовым номером. В зависимости от одноразового номера и того, что еще находится в блоке, функция хеширования выдаст хеш, который выглядит примерно так:

93ef6f358fbb998c60802496863052290d4c63735b7fe5bdaac821de96a53a9a

Для вас данный хеш может показаться очень длинным числом. (Это шестнадцатеричное число, то есть буквы A-F это цифры 10-15.) Для обеспечения нахождения блоков примерно каждые десять минут, существует так называемая цель сложности. Для создания действительного блока, ваш майнер должен найти хеш, который находится ниже цели сложности. Итак, если, например, целью сложности является

1000000000000000000000000000000000000000000000000000000000000000

то любое число, начинающееся с нуля, будет ниже цели, например:

0787a6fd6e0782f7f8058fbef45f5c17fe89086ad4e78a1520d06505acb4522f

Если мы снизим цель на

0100000000000000000000000000000000000000000000000000000000000000

то теперь нам нужны два нуля в начале чтобы оказаться ниже данной цифры:

00db27957bd0ba06a5af9e6c81226d74312a7028cf9a08fa125e49f15cae4979

Поскольку целью является такое громоздкое число с большим количеством цифр, люди обычно используют более простое число, чтобы выразить текущую цель. Данное число называется сложность майнинга. Сложность майнинга выражает, насколько сложнее является выработка текущего блока по сравнению с первым блоком. Таким образом, сложность 70000 означает то, что для генерации текущего блока вам нужно выполнить в 70000 раз больше работы, чем Сатоши Накамото, который сгенерировал первый блок. Справедливости ради следует отметить, что в то время майнинг оборудования и алгоритмы были намного медленнее и менее оптимизированы.

Для поддержания генарации блоков примерно каждые 10 минут, сложность корректируется с использованием общей формулы каждые 2016 блоков. Сеть пытается изменить его таким образом, чтобы 2016 блоков при текущей вычислительной мощности всемирной сети занимали около 14 дней. Вот почему, когда мощность сети растет, сложность также возрастает.

<h2>Аппаратура для биткойн майнинга</h2>

<strong>Процессор</strong>

В самом начале, добыча с помощью процессора была единственным способом добычи биткойнов и осуществлялась с использованием оригинального клиента Сатоши. В стремлении еще большей защиты сети и заработать больше биткойнов, майнеры внесли инновации по многим фронтам, и в последние годы майнинг с помощью процессоров стал относительно бесполезным. С помощью ваших ноутбуков вы можете добывать десятилетиями и не заработать ни единую монету.

<strong>Графический процессор</strong>

Примерно через полтора года после запуска сети было обнаружено, что высокопроизводительные графические карты были намного эффективнее при добыче биткойнов и после этого картина изменилась. Процессорный биткойн майнинг уступил место графическому процессору. Массивно параллельный характер некоторых графических процессоров позволил увеличить мощность биткойн майнинга в 50-100 раз при использовании гораздо меньшей мощности на единицу работы.

Несмотря на то, что для майнинга можно использовать любой современный графический процессор, линейка графических процессоров AMD оказалась намного лучше архитектуры nVidia для добычи биткойнов, а ATI Radeon HD 5870 в то время оказался наиболее экономичным выбором.

<strong>ПЛИС (FPGA)</strong>

Как и при переходе от центрального процессора к графическому процессору, мир биткойн-майнинга продвинул технологическую цепочку продуктов до программируемой логической интегральной схемы. С успешным запуском оборудования Butterfly Labs FPGA 'Single', аппаратурная среда биткойн-майнинга уступила место специально изготовленному оборудованию, предназначенному для добычи биткойнов.

Хотя ПЛИС и не насладилась 50-100-кратным увеличением скорости добычи, как это было при переходе от процессоров к графическим процессорам, они обеспечили преимущество благодаря энергоэффективности и простоте использования. Типичная графическая карта мощностью 600 MH/s потребляла 400 w энергии, тогда как типичное майнинг устройство ПЛИС обеспечивало скорость создания хешов в 826 MH/s при потреблении 80 w энергии.

Это 5-кратное улучшение позволило построить первые крупные фермы по добыче биткойнов с операционной прибылью. Появилась промышленность по добыче биткойнов.

<strong>СИМ (ASIC)</strong>

В настоящее время мир биткойн майнинга прочно перешел в эпоху специализированных интегральных микросхем (СИМ). СИМ - это чип, разработанный специально для выполнения одной единственной работы. В отличие от ПЛИС, СИМ нельзя перенастроить для выполнения других задач.

СИМ, разработанный для майнинга биткойнов всегда будет только добывать биткойны. Негибкость СИМ компенсируется тем, что он обеспечивает 100-кратное увеличение мощности хеширования при одновременном снижении энергопотребления по сравнению со всеми предыдущими технологиями.

В отличие от предыдущих поколений аппаратных средств, предшествующих СИМ, СИМ может стать «концом линии» в революционных майнинг технологиях. Процессоры были заменены графическими процессорами, которые, в свою очередь, сменились на ПЛИС, и далее на СИМ. Пока не создано ничего, что заменило бы СИМ на данный момент или даже в ближайшем будущем.

Ожидается постепенное усовершенствование продуктов СИМ и повышение его эффективности, но ничто не предвещает увеличение мощности хеширования от 50 до 100 раз или снижения энергопотребления в 7 раз, что было предложено при переходе с предыдущих технологий. Это делает потребление энергии на устройстве СИМ самым важным фактором среди всех продуктов СИМ, так как ожидаемый полезный срок службы майнинг устройства СИМ длиннее, чем вся история добычи биткойнов.

По всей видимости, приобретенное сегодня СИМ-устройство по-прежнему будет добывать биткойны через два года, при условии что устройство будет достаточно энергоэффективным, а стоимость электроэнергии не будет превышать его производимой мощности. Доходность майнинга также диктуется обменным курсом, но при любых обстоятельствах более энергоэффективное майнинг-устройство является более прибыльным. Если вы хотите попробовать свою удачу в биткойн-майнинге, то данный биткойн-майнер вероятно является наилучшим выбором.

<h2>Программное обеспечение для биткойн майнинга</h2>

Существуют два основных способа майнинга: самостоятельный майнинг или в качестве члена пула по добыче биткойнов; или с помощью договоров на облачный биткойн майнинг чтобы избежать мошенничества с использованием облачного биткойн-майнинга. Почти все майнеры выбирают вариант добычи в составе пула, потому что она сглаживает удачу, присущую процессу майнинга. Прежде чем присоединиться к пулу, убедитесь, что у вас есть биткойн-кошелек, чтобы было где хранить ваши биткойны. Затем вам нужно присоединиться к майининг пулу и настроить своего майнера (-ов) для подключения к этому пулу. При майнинге, прибыль от каждого блока, генерируемого любым членом пула, делится между членами пула в соответствии с количеством хешей, внесенных ими.

Сколько пропускной способности занимает биткойн? Если вы используете биткойн майнер для добычи с пулом, объем должен быть незначительным, примерно 10 MB в день. Тем не менее, вам обязательно нужна исключительная возможность подключения, чтобы вы получали любые обновления по работе как можно скорее.

Это дает членам пула более частую и стабильную выплату (это называется уменьшением вашего отклонения), но ваши выплаты могут быть уменьшены на любую сумму, которую может взимать пул. Одиночная добыча даст вам большие и редкие выплаты, а добыча с в пуле даст вам небольшие, но частые выплаты, но в обеих случаях результат будет иметь одинаковую сумму если вы находитесь в пуле с нулевой платой в долгосрочной перспективе.

<h2>Облачный биткойн-майнинг</h2>

Покупая контракты на облачный биткойн майнинг, инвесторы могут зарабатывать биткойны, не имея дело с проблемами аппаратного и программного обеспечения, электроэнергии, пропускной способности или других внесетевых проблем.

Перечисление в этом разделе НЕ является поддержкой этих услуг и всего лишь служит в качестве сравнения облачного биткойн майнинга. В последнее время было огромное количество случаев мошшеничества связанного с облачным биткойн майнингом.

<strong><a href="http://geni.us/hashflare">Обзор Hashflare</a></strong>: Hashflare предлагает майнинг договора SHA-256 и можно добывать более прибыльные монеты SHA-256, в то время как автоматические выплаты по-прежнему осуществляются в биткойнах (BTC). Клиенты должны приобрести не менее 10 GH/s.

<strong><a href="http://geni.us/advendorgm">Обзор Genesis Mining</a></strong>: Genesis Mining является крупнейшим поставщиком биткойнов и scrypt-облачного майнинга. Genesis Mining предлагает три плана облачного майнинга биткойнов по разумным ценам. Также доступны майнинг договора Zcash.

<strong><a href="http://geni.us/hashing24">Обзор Hashing24</a></strong>:  Hashing24 занимается биткойн майнингом с 2012 года. У них есть производственные мощности в Исландии и Грузии. Они используют современные СИМ-чипы от BitFury, которые обеспечивают максимальную производительность и эффективность.

<h2>Что такое биткойн-майнинг?</h2>

<center><img src="/images/what-is-bitcoin-mining.png" alt="bitcoin mining saga" /></center>

Биткойн майнинг - это процесс добавления записей транзакций в публичный журнал биткойна с прошлыми транзакциями. Данная книга прошлых транзакций называется блокчейном (цепочка блоков), так как она представляет собой блочную цепочку. Блокчейн служит для подтверждения осуществления транзакций для остальной сети.

Биткойн узлы используют блокчейн чтобы отличать законные биткойн транзакции от попыток повторного использования монет, которые уже были потрачены в другом месте.

Биткойн майнинг специально сконструирована так, чтобы быть ресурсоемкой и сложной, так чтобы количество блоков, выявляемых майнерами каждый день, оставалось неизменным. Отдельные блоки должны содержать доказательство работы чтобы работа считалась действительной. Данное доказательство работы проверяется другими узлами биткойнов каждый раз, когда они получают блок. Биткойн использует функцию проверки работы hashcash.

Основная цель майнинга заключается в том, чтобы позволить узлам биткойнов достичь безопасной, устойчивой к взлому согласованности. Майнинг также является механизмом, используемым для внедрения биткойнов в систему: майнерам выплачивают любые транзакционные платежи, а также «субсидию» от новосозданных монет.

Это служит целям распространения новых монет на децентрализованной основе, а также мотивирования людей к обеспечению безопасности системы.

Биткойн майнинг (добыча) называется так, потому что она напоминает добычу других сырьевых материалов: она требует усилие, и таким образом потихоньку получается новая валюта, доступная по курсу, напоминающему курс, по которому с земли добываются сырьевые материалы, такие как золото.

<h2>Что такое доказательство работы?</h2>

<center><img src="/images/what-is-proof-of-work.png" alt="bitcoin mining saga" /></center>

Доказательство работы представляет собой частицу данных, которую было трудно (дорогостояще, трудоемко) произвести с тем чтобы удовлетворить определенные требования. Проверка того отвечает ли информация указанным требованиям должна стать обыденной вещью.

Получение доказательства работы может быть случайным процессом с малой вероятностью, так что в среднем требуется много попыток и ошибок, прежде чем будет создано действительное доказательство работы. Биткойн использует функцию проверки работы hashcash.

<h2>Что такое сложность биткойн майнинга?</h2>

<center><img src="/images/what-is-bitcoin-mining-difficulty.png" alt="bitcoin mining saga" /></center>

<h2>Вычислительно-сложная проблема</h2>

Биткойн добыча блока является трудным процессом поскольку хеш SHA-256 блочной головки должен быть ниже или равен цели, чтобы блок был принят сетью.

Эту проблему можно упростить в целях разъяснения: хеш блока должен начинаться с определенным количеством нулей. Вероятность вычисления хеша, который начинается со многих нулей, очень низкая, поэтому необходимо сделать много попыток. С целью генерации нового хеша в каждом круге, значение одноразового номера увеличивается. Для получения подробной информации см. Доказательство работы.

<h2>Метрика сложности биткойн сети</h2>

Сложность биткойн сети является мерой того, насколько сложно найти новый блок по сравнению с самым легким существующим путем нахождения блока. Она пересчитывается каждые 2016 блоков в такое значение, что предыдущие 2016 блоков были бы сгенерированы ровно в течении двух недель, при условии, что все майнеры осуществляли майнинг на этом уровне сложности. Это в среднем будет выдавать один блок каждые десять минут.

По мере того, как присоединяется больше майнеров, скорость создания блоков будет расти. По мере того как скорость генерации блоков увеличивается, возрастает сложность компенсации, что приведет к снижению скорости создания блока. Любые блоки, выпущенные злоумышленниками, которые не соответствуют заданной цели сложности, будут просто отвергнуты всеми в сети и, следовательно, будут бесполезны.

<h2>Блочная награда</h2>

При обнаружении блока, его первооткрыватель может присвоить себе определенное количество биткойнов, что является общей согласованной практикой среди всех майнеров в сети. В настоящее время данный размер щедрости составляет 25 биткойнов; это значение будет уменьшаться вдвое через каждые 210 000 блоков. См. Управляемый запас валюты или воспользуйтесь биткойн майнинг калькулятором.

Кроме того, майнер получает вознаграждение, выплачиваемое пользователями, отправляющими транзакции. Плата является стимулом для майнера для включения транзакции в свой блок. В будущем, по мере того, как количество новых биткойн-майнеров получающих разрешение создавать в каждом блоке сократится, плата будет составлять гораздо более больший процент от дохода от добычи.

<h2>Благодарим</h2>

Blitzboom и ребят из # bitcoin-dev за помощь в написании данного руководства!