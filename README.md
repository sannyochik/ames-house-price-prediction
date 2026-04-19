# ames-house-price-prediction
House price prediction on the Ames Housing dataset.

Проект по прогнозированию стоимости недвижимости с датасетом House Prices - Advanced Regression Techniques

## Задача
Построить модель регрессии для предсказания "SalePrice" на табличных данных о характеристиках домов.

Используются:
- `train.csv`
- `test.csv`
- `sample_submission.csv`

## Что сделано
- первичный анализ данных
- анализ распределения целевой переменной
- обработка пропусков
- генерация новых признаков
- построение preprocessing pipeline
- обучение модели `GradientBoostingRegressor`
- hold-out validation
- cross-validation
- анализ важности признаков
- генерация submission-файла для Kaggle

## Модель
Основная модель:
- `GradientBoostingRegressor`

## Метрики
- Public Kaggle Score: **0.12802**
- Метрика соревнования: RMSE по логарифму цены

## Стек
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
