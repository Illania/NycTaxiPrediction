# New York City Taxi Trip Duration
## Проектный практикум 2 семестр

![](header.png?raw=true "")

### Постановка задачи

Вам предстоит решить настоящую задачу машинного обучения, направленную на автоматизацию бизнес процессов. Мы построим модель, которая будет предсказывать общую продолжительность поездки такси в Нью-Йорке.

Представьте вы заказываете такси из одной точки Нью-Йорка в другую, причем не обязательно конечная точка должна находиться в пределах города. Сколько вы должны будете за нее заплатить? Известно, что стоимость такси в США рассчитывается на основе фиксированной ставки + тарифная стоимость, величина которой зависит от времени и расстояния. Тарифы варьируются в зависимости от города.

В свою очередь время поездки зависит от множества факторов таких как, откуда и куда вы едете, в какое время суток вы совершаете вашу поездку, погодных условий и так далее.

Таким образом, если мы разработаем алгоритм, способный определять длительность поездки, мы сможем прогнозировать ее стоимость самым тривиальным образом, например, просто умножая стоимость на заданный тариф. Сервисы такси хранят огромные объёмы информации о поездках, включая такие данные как конечная, начальная точка маршрута, дата поездки и ее длительность. Эти данные можно использовать для того, чтобы прогнозировать длительность поездки в автоматическом режиме с привлечением искусственного интеллекта.

Бизнес-задача: определить характеристики и с их помощью спрогнозировать длительность поездки такси.

Техническая задача для вас как для специалиста в Data Science: построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать числовой признак - время поездки такси. То есть решить задачу регрессии.

### Основные цели проекта:

Сформировать набор данных на основе нескольких источников информации
Спроектировать новые признаки с помощью Feature Engineering и выявить наиболее значимые при построении модели
Исследовать предоставленные данные и выявить закономерности
Построить несколько моделей и выбрать из них наилучшую по заданной метрике
Спроектировать процесс предсказания времени длительности поездки для новых данных
Загрузить свое решение на платформу Kaggle, тем самым поучаствовав в настоящем Data Science соревновании. Во время выполнения проекта вы отработаете навыки работы с несколькими источниками данных, генерации признаков, разведывательного анализа и визуализации данных, отбора признаков и, конечно же, построения моделей машинного обучения!
