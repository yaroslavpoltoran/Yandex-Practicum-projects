# Создание моделей для предсказания рыночной стоимости автомобиля

## Описание проекта

Создается приложение, в котором можно быстро рыночную стоимость своего автомобиля. В распоряжении имеются исторические данные: технические характеристики, комплектации и цены автомобилей. Нужно построить модель для определения стоимости.

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.

## Описание хода работы

Первым этапом была предобработка. Датасет содержал большое количество пропусков и выбросов (например, мощность машины в 20000 л.с.), типы данных не соотвествовали столбцам. Некоторые пропуски были удалены, некоторые заполнены наиболее подходящими значениями.

После данные были подготовлены для использования в моделях и были исследованы раздичные модели машинного обучения. Так как в проекте было важно не только качество предсказания, но и скорость обучения, для каждой модели было замерено время. Результаты сведены в общую таблицу и по итогу была выбрана оптимальная модель.

В проекте использовались следующие библиотеки: Pandas, Numpy, Scikit-Learn, LightGBM, CatBoost.