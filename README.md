# Выборы 2020

Данные президентской избирательной кампании в Республики Беларусь в 2020 году.

## Задачи

В этой избирательной кампании обнаружилось курьезное несовпадение данных ЦК по выборам и данных самих выдвиженцев о количестве подписей избирателей, собранных за выдвижение кандидатом в президенты и поданных в ЦК. В некоторых случаях превышение достигало нескольких десятков тысяч подписей, а выдвиженцы вели себя не менее загадочно: опровергали свои ранее сделанные подсчеты и соглашались с "новыми" данными ЦК или настаивали на своем прежнем количестве сданных подписей. Подробнее см. https://news.tut.by/economics/691564.html и https://news.tut.by/economics/691021.html

Эта загадка нуждается в каком-то объяснении. Предположительно, разгадку можно найти в подробных сведениях о количестве избирателей, поставивших подписи в поддержку выдвижения кандидатом в Президенты Республики Беларусь (см. раздел **Данные**).

### Гипотезы

0. Правы выдвиженцы (Черечень), а подписи собираются в единый пул и потом из него заново распределяются согласно заранее заданным квотам. Если это так, то в распределении подписей проявятся какие-то закономерности. При этом ЦК может быть официально не в курсе, т.к. все происходит на другом уровне или вообще в некой параллельной структуре.
1. Выдвиженцы плохо контролируют свои инициативные группы и не знают точное число сданных подписей. Гипотезу трудно проверить, т.к. доступа к сданным подписям нет, а есть только данные ЦК. Но если в распределении данных ЦК не обнаружится закономерностей, то будет уже что-то. 

### Сведения о количестве подписей за выдвижение кандидатом собраны по:

- Всей Республике
- Всем областям на областном уровне
- Минску, Минской и Витебской областям на уровне районов областного починения и районов в городах областного подчинения

## Данные

В папке data содержатся машиночитаемые данные:

- [zajaviteli_init_grupp.csv](data/zajaviteli_init_grupp.csv) - Сведения о лицах, подавших заявления о регистрации инициативных групп граждан по выдвижению кандидатов в Президенты Республики Беларусь
- [podpisi.csv](data/podpisi.csv) - Сведения об установлении количества избирателей, поставивших подписи в поддержку выдвижения кандидатом в Президенты Республики Беларусь 
- [podpisi_legenda.csv](data/podpisi_legenda.csv) - Расшифровка названий полей в наборе данных (чтобы отфильтровать данные на уровне всей республики или только областей, нужно выбрать строки со значением поля rajon == None)

## Источники

- [rec.gov.by](http://rec.gov.by) - официальный сайт ЦК по выборам
- [vybary2020.by](http://vybary2020.by/) - официальный сайт избирательной кампании 2020 года 

## Опорные даты кампании, связанные с публикацией данных

- около 27 мая - Опубликование в печати решений об образовании территориальных комиссий
- около 5 июля - Опубликование в печати решений об образовании участковых комиссий
- около 19 июля - Передача в печать для опубликования сообщения о регистрации кандидатов в Президенты Республики Беларусь
- около 19 июля - Представление в печатные СМИ, определенные Центральной комиссией, текстов предвыборных программ для опубликования
- После 9 августа - Публикация итогов выборов (в зависимости от итогов первого тура)






