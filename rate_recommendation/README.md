# Рекомендация система для телеком компании (рекомендация тарифов)

## Цель проекта
Проанализировать данные о поведении клиентов, перешедших на новые тарифы мобильной связи и построить модель, предлагающую пользователям архивных тарифов наиболее подходящий им новый тариф ("Тариф-1" или "Тариф-2").

## Вывод
Обучены разные модели, проверено их качество и выбрана модель с максимальной долей правильных ответов (Random Forest Classifier). 
Качество выбранной модели проверено на тестовой выборке, accuracy = 0.809 (что соответствует требованию - accuracy не менее 0.75). 
Проверена и подтверждена адекватность выбранной модели.

## Используемые библиотеки
- Pandas
- Numpy
- Sweetviz
- Matplotlib
- Seaborn
- Sklearn (модели LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, GradientBoostingClassifier, DummyClassifier)
- Catboost

дополнительно при реализации проекта использованы следующие методы библиотеки Sklearn: 
Pipeline, GridSearchCV, StratifiedKFold, shuffle

## Статус
- [x] Завершен