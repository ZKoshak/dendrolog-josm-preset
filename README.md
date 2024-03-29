# ![icon](https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Forestry_Le%C5%9Bnictwo_%28Beentree%292.svg/50px-Forestry_Le%C5%9Bnictwo_%28Beentree%292.svg.png)Дендролог
Набор заготовок для [JOSM](https://josm.openstreetmap.de/), облегчающие и унифицирующие тегирование деревьев и кустарников.

!NB! Данные заготовки предназначены для проекта [Плантарий:Открытая карта растений(Plantarium:Open Plant Map)](http://opm.zkoshak.linkpc.net). При их использовании для OpenStreetMap, следует учитывать возможность расхождений из-за ошибок в принятой осмерами некорректной схеме тегирования.

В настоящий момент включает следующие заготовки:
* RUS:Дендролог — деревья произрастающие в России ([raw](https://raw.githubusercontent.com/ZKoshak/dendrolog-josm-preset/master/rus-dendrolog.xml))
* RUS:Dendrolog — многоязыковая облегчённая(без описаний) версия RUS:Дендролога ([raw](https://raw.githubusercontent.com/ZKoshak/dendrolog-josm-preset/master/rus-dendrolog(int).xml))
* Дендролог.СПб — деревья произрастающие в Санкт-Петербурге ([raw](https://raw.githubusercontent.com/ZKoshak/dendrolog-josm-preset/master/dendrolog_spb.xml))
* Dendrolog.SPb — многоязыковая облегчённая(без описаний) версия Дендролога.СПб ([raw](https://raw.githubusercontent.com/ZKoshak/dendrolog-josm-preset/master/dendrolog_spb(int).xml))

### Персоналии
- [Артём «Зелёный Кошак» Крюковский (ZKoshak)](https://github.com/ZKoshak) — начальная разработка
- [контрибутеры](https://github.com/ZKoshak/dendrolog-josm-preset/graphs/contributors)

## Установка
* JOSM: Настройки > Параметры проекции (третье сверху) > Заготовки тегов > `+` у правой панели `Активные заготовки`, указываем название пресета и путь к скаченному файлу заготовки или URL на raw.
* Vespucci: Настройки(значёк в виде шестерёнки) > Дополнительно:Заготовки > Добавить заготовку > указываем название пресета и URL на raw.

## Редактирование
Ознакомьтесь с [рекомендациями по редактированию](CONTRIBUTING.md)

После изменения файла не забудьте обновить дату в начале, в поле `version`. Если за день выпускаете много версий — обновите число после даты.

#### Проверьте на ошибки
Для этого достаточно подключить файл с заготовкой локально. В момент добавления при нажатии `Ok` пройдут проверки, и если что-то не понравится, то JOSM ругнётся ошибкой с указанием строки.

Для удобства во время редактирования можно воспользоваться плагином JOSM [tagging-preset-tester](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/tagging-preset-tester). В нём есть возможность смотреть экранные формы и подгружать изменения через кнопку `Обновить`, а не перезагрузкой JOSM.

## Благодарности =)
- Александр Панкратов — за идею и неугомонность
- Alexander Istomin — за болванку "ридми"
- Anton Belichkov — за "когда будет заготовка"
- fr1 — за "критику"
- участникам OSM и чЯтика
