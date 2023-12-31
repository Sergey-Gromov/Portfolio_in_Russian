## Выбор локации для скважины.
**Цель проекта:**  

Разработать для сотрудников нефтедобывающей компании модель, помогающую принять решение, где бурить новую скважину.

Для проекта есть в наличии пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.

В рамках проекта будет построена модель машинного обучения с использованием линейной регрессии, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Анализ возможной прибыли и риски будут проанализированы техникой Bootstrap.

**Навыки и инструменты:**  
python  
pandas  
numpy  
sklearn.model_selection.train_test_split  
sklearn.linear_model.LinearRegression  
sklearn.metrics.mean_squared_error  

**Общий вывод:**
- Из трех регионов только регион 1 (geo_data_1) показал уровень риска меньше заданого критерия 2.5%, и соответственно он один должен быть отобран.
- Также из трех регионов именно регион 1 показал наибольшую среднюю прибыль.
- Кроме того, в данном регионе 1 наблюдается самый низкий доверительный интервал.
- Также следует учесть, что в регионе 1 наблюдается самая высокая точность предсказаний модели

На основании построенной в рамках данного проекта модели рекомендуется выбрать регион 1.
