# Исследвание по выбору локации бурения скважины для нефтедобывающей компании

## Цель проекта
На основании характеристик нефтяных скважин и проб нефти построить модель, определяющую регион, где нефтедобыча принесет максимум прибыли.

## Вывод
Проанализированы предоставленные наборы исторических данных добывающей компании «ГлавРосГосНефть» по регионам добычи нефти.

Для каждого региона построена модель Линейной регрессии. Для региона geo_data_1 модель показала наилучшее значение качетсва по метрике RMSE. Качество метрики в двух остальных регионах практически одинаково хуже в сравнении с регионом geo_data_1.

Реализован бизнес-алгоритм по выбору 200 наиболее рентабельных скважин, среди отобранных 500, по которым бизнес-заказчик может провести анализ. С помощью техники Bootstrap рассчитана средняя выручка, 95%-ый доверительный интервал и вероятность убыточного риска.

Анализ показателей убыточности показал, что добыча в регионе geo_data_1 будет безубыточна со средней выручкой не ниже выделенного бюджета. Данный регион (набор данных geo_data_1) предлагается к выбору для разработки скважин.

## Используемые библиотеки
- Pandas
- Numpy
- Pandas_profiling
- Scipy
- Sklearn (LinearRegression, StandardScaler, GridSearchCV, Pipeline)
- Seaborn
- Matplotlib

## Статус
- [x] Завершен