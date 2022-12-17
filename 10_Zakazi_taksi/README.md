Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час с использованем модели предсказания, чтобы значение метрики RMSE на тестовой выборке было  не больше 48.

В ходе выполенения данного проекта предсказано значение целевой величины на основе данного временного ряда (заказов такси на следующий час). Произведен первичный анализ данных, их соответсвующее преобразование, выделение признаков, необходимых для последующего предсказания.Также выделены и проанализированы сезонная и трендовые компоненты временного ряда. Реализованы 2 функции: по подбору признаков скользящего окна и сдвигов, по подбору параметров случайного леса для каждого набора признаков и определния качества работы моделей на тестовых данных. В итоге наилучшее значение метрики для тестовых данных у модели случайного леса дало значение 41.1213, что меньше (48) требуемого почти на 15%.