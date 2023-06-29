# Восстановление золота из золотосодержащей руды

[HTML](https://github.com/aq2003/Portfolio/blob/main/Gold%20Recovery/P9_Portfolio.html)     [ipynb](https://github.com/aq2003/Portfolio/blob/main/Gold%20Recovery/P9_Portfolio.ipynb)

## Описание проекта

Нужно подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении имеются данные с параметрами добычи и очистки. Модель должна помочь оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_absolute_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**


## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.