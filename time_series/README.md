# Прогнозирование заказов такси

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час

## Задача
Построить модель предсказания количества заказов такси на следующий час со значением метрики RMSE не более 48.

## Данные
- время
- количество заказов

## Используемые библиотеки
- pandas - для работы с датафреймами
- numpy - для расчета дисперсии и стандартного отклонения
- matplotlib.pyplot - для работы с графиками
- seaborn - для построения множественных графиков.
- sklearn.metrics - для метрики
- sklearn.model_selection - для разделение на выборки, кроссвалидацию 
- sklearn.tree - для решающего дерева
- sklearn.linear_model - для линейной регрессии
- statsmodels.tsa.seasonal - для выявления трендов и сезонности
