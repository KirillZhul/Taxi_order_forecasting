# taxi_order_forecasting
Прогнозирование заказов такси

### Описание задачи
Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. 
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. 
Постройте модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.

Вам нужно:
- Загрузить данные и выполнить их ресемплирование по одному часу.
- Проанализировать данные.
- Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.
- Проверить данные на тестовой выборке и сделать выводы.

Данные лежат в файле taxi.csv. 
Количество заказов находится в столбце num_orders (от англ. number of orders, «число заказов»).
