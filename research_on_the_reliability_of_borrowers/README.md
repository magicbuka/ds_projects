# Исследование надёжности заёмщиков — анализ банковских данных

## Цель проекта
На основе банковских статистических данных о платёжеспособности клиентов выяснить, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Результаты исследования будут использованы при внедрении системы кредитного скоринга, оценивающей способность потенциального заёмщика вернуть кредит.

## Вывод
Анализ данных показал наличие ошибок ввода данных, сознательное неуказание значений в колонках "количество отработанных дней" и "уровень заработной платы". 
В качестве результата исследования составлен портрет типичного пользователя, имеющего максимальный риск невозврата кредита для банка:
- имеет 1-3 детей
- проработал не более 1 месяца
- по возрасту относится к категории "молодежь" (18-36 лет)
- начальное, среднее или неоконченное высшее образование
- семейный статус "не женат / не замужем" или "гражданский брак"
- мужской пол
- тип занятости "другое" ('безработный', 'предприниматель', 'студент' или 'в декрете')
- средний или ниже среднего заработок (от 75'000 до 200'000)
- цель взятия кредита "автомобиль" или "образование"

## Используемые библиотеки
- Pandas
- Numpy
- PyMystem3
- Pandas_profiling
- Sweetviz
- Sklearn
- Missingo

## Статус
- [x] Завершен
