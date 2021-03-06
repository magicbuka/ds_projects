# Исследование объявлений о продаже квартир в Санкт-Петербурге

## Цель проекта
Проанализировать архив объявлений о продаже квартир в Санкт-Петербурге и Ленинградской области, установить параметры, влияющие на стоимость объекта недвижимости, для построения системы, отслеживающей аномалии и мошенничество.

## Вывод
На формирование рыночной стоимости объектов недвижимости влияют следующие параметры:

- площадь - чем больше площадь, тем выше цена
- удалённость от центра/аэропорта - чем ближе к центру Санкт-Петербурга (радиус центра - 3 км) и быстрее добираться до аэропорта, тем выше цена
- наличие прудов и парков в радиусе 3 км
- на каком этаже расположена квартира - меньше всего ценятся с расположением на первом этаже
- день недели и месяц размещения объявления (первая половина недели и конец зимы-весна, соответственно, являются периодами с более высокими ценами)
- экономическая ситуация в стране, способная повлиять на стоимость недвижимости

## Используемые библиотеки
- Pandas
- Numpy
- PyMystem3
- Pandas_profiling
- Matplotlib
- Сufflinks
- Seaborn
- Missingno
- Sklearn
- Re

## Статус
- [x] Завершен