# Linear Regression (Python)

Учебный проект по Machine Learning: реализация линейной регрессии для предсказания стоимости недвижимости на Python.

## Возможности

- Анализ датасета (4600 объектов, 18 столбцов).
- Очистка данных от нулевых значений и выбросов.
- Feature Engineering: создание признаков `age` и `renovated`.
- Обучение модели `LinearRegression`.
- One-Hot Encoding категориальных признаков.
- Логарифмическое преобразование целевой переменной.
- Визуализация реальных и предсказанных цен.

## Результаты

Лучшая модель использует почтовый индекс (statezip) и логарифмирование целевой переменной.

| Метрика   | Результат|
|-----------|----------|
|`R² (Test)`| 0.762    |
|`RMSE`     | $139,035 |
| `MAE`     | $86,379  |

## Используемые технологии

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

## Структура проекта

| Файл | Назначение |
|---|---|
| `LinReg1.ipynb` | Анализ данных и обучение модели |
| `data.csv` | Исходный датасет |

## Запуск

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook LinReg1.ipynb
```

## Автор

[TigerKick12](https://github.com/TigerKick12), студент Computer Science, КазНУ им. аль-Фараби.
## Автор

[TigerKick12](https://github.com/TigerKick12), студент Computer Science, КазНУ им. аль-Фараби.
