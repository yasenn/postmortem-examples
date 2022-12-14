# The cause of the burnout: based on the results of the OVH data center fire investigation 

[The cause of the burnout: based on the results of the OVH data center fire investigation - Linxdatacenter](https://linxdatacenter.com/en/news-and-publications/ovh-dc-fire)

Due to the lack of a main switch, it took around 3 hours to turn off the power supply of the data center. The UPS inverters were energized for all that time and some servers continued to work.

# подобные случаи

```
У меня был в практике подобный кейс, не помню, рассказывал ли, когда здание обесточило, ДГУ завёлся, но не сработал АВР. Таким образом сервера продолжали работать на ИБП, а вся инфраструктура ЦОД - нет. То есть охлаждение сдохло, а пожаротушение, как оказалось было с невыдернутой чекой(как уже потом выяснилось). Когда я зашёл в гермозону - температура была выше сотни градусов(термометры на стойках показывали Err). Пришлось тушить всё на горячую.
```

## 35 тонн топлива в офисном здании China Telecom

[Пожары в дата-центрах. Как выстроить надёжное резервирование? / Хабр](https://habr.com/ru/company/ruvds/blog/690566/)

Когда 16 сентября 2022 года [загорелся небоскрёб China Telecom](https://abcnews.go.com/International/wireStory/fire-engulfs-42-story-building-china-deaths-reported-90008978) со столбом пламени в десятки метров и взрывами, то первым делом возник вопрос — что так сильно горит в 42-этажном офисном здании? Вскоре выяснилось, что здание не совсем офисное. Оказалось, на нескольких этажах размещался ЦОД. А все мы знаем, что по [правилам резервирования Tier 2](https://uptimeinstitute.com/tiers) дата-центр обязан хранить запасные энергоносители на случай отключения основного питания.  
  
Что такое «запасные энергоносители»? Это могут быть заряженные аккумуляторы, ну, или дизельное топливо…  
  
По [предварительным оценкам](https://gagadget.com/en/167559-china-telecom-skyscraper-burned-down-in-20-minutes-it-was-storing-35-tons-of-fuel-for-servers/), в здании China Telecom на момент возгорания могло быть около 35 тонн дизельного топлива. В результате, фасад 220-метрового небоскрёба в городе Чанша провинции Хунань выгорел буквально за 20 минут.  
  

  
Цистерны с дизтопливом в офисном здании — совершенно невероятная картина, но в Китае и не такое можно представить.


## ovh

[Пожары в дата-центрах. Как выстроить надёжное резервирование? / Хабр](https://habr.com/ru/company/ruvds/blog/690566/)

Ещё не стёрся в памяти [cгоревший дата-центр OVHCloud в Страсбурге](https://habrastorage.org/getpro/habr/upload_files/829/cec/679/829cec6794eb7d8e26ac21c0e0d39605.jpg) в 2021 году.  
  
![](https://habrastorage.org/r/w1560/webt/cp/rm/lh/cprmlhlbsal5zn8aoed7g7wpreo.jpeg)  
  
Здание SBG-2 было частью кампуса SBG из четырёх ЦОД. В нём предоставлялись услуги аренды выделенных серверов (dedicated) и облачные сервисы. В пожаре были уничтожены 15 000 серверов.

## российские ДЦ:

[Пожары в дата-центрах. Как выстроить надёжное резервирование? / Хабр](https://habr.com/ru/company/ruvds/blog/690566/)

Из российских происшествий многие помнят [возгорание кровли в дата-центре Dataline на Боровой](https://www.tadviser.ru/index.php/%D0%9F%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82:%D0%A6%D0%9E%D0%94_DataLine_%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D0%B0_%D0%91%D0%BE%D1%80%D0%BE%D0%B2%D0%B0%D1%8F,_7) («Одноклассники», Mail.ru), пожары [в дата-центре Selectel в Санкт-Петербурге](https://www.fontanka.ru/2016/03/16/116/) («Вконтакте»), [дата-центре «Технологии Будущего»](https://habr.com/ru/post/89172/) (где размещались восемь хостингов, так что из-за пожара ушло в офлайн около 2500 веб-сайтов разных компаний) и много других аварий как у нас, так и за рубежом.  
  
![](https://habrastorage.org/r/w1560/webt/zw/jm/0y/zwjm0yfntoaywbzlrdb3zbl6gek.jpeg)  
_Место, где начался пожар в дата-центре Dataline (5 июня 2019 года)_

## 2022.08 - google - электрическая дуга

[Пожары в дата-центрах. Как выстроить надёжное резервирование? / Хабр](https://habr.com/ru/company/ruvds/blog/690566/)

8 августа 2022 года в [дата-центре Google г. Каунсил-Блафс](https://www.google.com/about/datacenters/locations/council-bluffs/) (штат Айова) произошёл взрыв с человеческими жертвами (трое раненых с серьёзными ожогами). В результате поиск и картографический сервис Google на непродолжительное время стали недоступны в разных частях света. По информации пользователя Council Bluffs Scanner, который прослушивает радиопереговоры спасателей и полиции в своём городке, причиной стал «крупный электрический взрыв без возникновения пожара» на территории ЦОДа.  
  

Электрический взрыв — возникновение электрической дуги огромной мощности. Причины инцидента неизвестны. Возможно, это связано с аномальной жарой, которая стояла в Айове.


## Выпуск газа - Nasdaq Nordic
[Пожары в дата-центрах. Как выстроить надёжное резервирование? / Хабр](https://habr.com/ru/company/ruvds/blog/690566/)

  
Ещё одна необычная авария [случилась](https://www.datacenterdynamics.com/en/news/fire-suppression-failure-at-digiplex-brings-down-nordic-nasdaq/) в апреле 2018 года в новеньком дата-центре DigiPlex (на севере Стокгольма), который обслуживает систему хранения данных фондовой биржи Nasdaq Nordic. Из-за ошибочного включения системы газового пожаротушения произошёл выпуск газа, а ударная волна вывела из строя дисковые накопители серверов.  
  
Авария привела к остановке торгов Nasdaq Nordic на пять часов.



## Глобальные сбои облачных провайдеров

  
У облачных провайдеров тоже случаются сбои. При этом выходят из строя службы, которые должны масштабироваться в разных дата-центрах.  
  
Например, 13 марта 2019 года случился [глобальный сбой](https://www.theguardian.com/technology/2019/mar/13/googles-gmail-and-drive-suffer-global-outages) в обслуживании почты Gmail и файлового хранилища Google Drive, которые полностью ушли в офлайн на несколько часов. Причины не назывались.  
  
В результате упомянутого ранее инцидента с молниями в Техасе временно вышел из строя крупный дата-центр Azure. Перебои в работе облачного сервиса Microsoft продолжались несколько дней.  
  
В ноябре 2020 года сбой AWS в регионе US-EAST-1 [положил значительную часть интернета](https://www.theverge.com/2020/11/25/21719396/amazon-web-services-aws-outage-down-internet). Сервисы AWS начали выходить из строя 25 ноября около 11:00 ET. По информации AWS, первым упал Kinesis Data Streams, потянув за собой всё остальное: ACM, Amplify Console, API Gateway, AppStream2, AppSync, Athena, CloudFormation, CloudTrail, CloudWatch, Cognito, Connect, DynamoDB, EventBridge, IoT Services, Lambda, LEX, Managed Blockchain, Resource Groups, SageMaker, Support Console и Workspaces. Полная работоспособность восстановили только в 4:16 на следующий день, то есть даунтайм продолжался почти сутки. Пострадали тысячи сайтов, сервисов и мобильных приложений, которые размещают бэкенд на AWS, включая [1Password](https://twitter.com/1Password/status/1331697241132847105), [Adobe Spark](https://twitter.com/AdobeSpark/status/1331644328947552263), [Autodesk](https://twitter.com/autodesk/status/1331664145301852163), [Coinbase](https://twitter.com/CoinbaseSupport/status/1331679494378164224), [Glassdoor](https://twitter.com/Glassdoor/status/1331672377470701568), [Flickr](https://twitter.com/FlickrHelp/status/1331636739513978882), [iRobot](https://twitter.com/iRobot/status/1331667670383685635), [Roku](https://twitter.com/RokuSupport/status/1331649921557041152) и др.  
  
Другой крупный сбой AWS произошёл [в июне 2021 года](https://www.engadget.com/a-huge-outage-is-affecting-large-swaths-of-the-internet-102354305.html). Тогда ненадолго ушли в офлайн многие популярные сайты, как Twitch, Reddit, Twitter, Hulu, HBO Max, Shopify и Amazon.  
  

В принципе, нет особых причин полагать, что облачные центры данных будут выходить из строя реже, чем отдельные серверы, установленные у себя (on-prem). С одной стороны, в коммерческих дата-центрах формально действуют правила резервирования питания и дублирования всех важных систем. С другой стороны, в нежилых помещениях ЦОДов выше вероятность инцидента: там больше горючих материалов, больше нагрузка на оборудование, больше посторонних сотрудников и больше причин для инцидентов, чем у вас в офисе или дома (хотя бывает и наоборот).  
  
Получается, что в любом случае клиент должен сам думать о резервировании данных. Никакой ЦОД или отдельное облако не даёт полной гарантии. Требуется **резервирование в глобальном масштабе**.
