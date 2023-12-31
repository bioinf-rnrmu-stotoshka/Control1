# Контрольная работа №1

## Общие требования
На контрольную работу даётся **один** час. **Не забывайте отправлять промежуточные результаты.** Разрешено пользоваться любыми источниками, кроме программ, генерирующих код (по типу ChatGPT). 
Работа выполняется **самостоятельно**, списывать у товарищей и совещаться с ними запрещается. 
Всего 3 варианта. Необходимо сдать:
 - код (R или Rmd)
 - очищенный датасет (csv, разделитель - точка с запятой), который необходим для решения задачи (т.е. это может быть не весь датасет)
 - требуемый график (png)
   
Обязательно указывайте формулировку задания. Код должен быть минимально документирован, с ответами на доп.вопросы.
Давайте осмысленные имена переменным, не делайте лишних операций, не забывайте про отступы и пробелы. 
Хорошо отформатированный код легче проверять, облегчает отладку и понимание происходящего, улучшает восприятие, поднимает оценку.
Проверяйте данные на:
 - Неправильный тип данных
 - Пропущенные значения
 - Аномальные значения
 - Противоречивые значения.
 - Дублирование данных

Подсказка: необязательно работать с всем набором данных.
Выводы делайте на основании наблюдаемых значений. Не нужно проводить никаких стат.тестов!
Не забывайте про оформление графиков. Названия, подписи, легенды!
Данные располагаются в папке ***data***, спецификация к данным - в папке ***specification***
## Распределение вариантов

|Фамилия|Номер|
|------------|---|
| Антипова   | 1 |
| Афанасьев  | 2 |
| Белова     | 3 |
| Белянкина  | 1 |
| Вакарюк    | 2 |
| Ворокова   | 3 |
| Гришина    | 1 |
| Дмитриев   | 2 |
| Кулагина   | 3 |
| Масалов    | 1 |
| Панкратова | 2 |
| Рахимова   | 3 |

### Вариант 1
Датасет посвящен динамике рапространения COVID-19 в Румынии (broken_covid.csv). Ваша задача - посмотреть была ли положительная динамика в апреле-мае (доля и количество умерших падает, доля и количество выздоровевших растет).
1) Подготовьте данные
2) Постройте на одной (!) панели (девайсе) графики зафисимостей долей/количества умерших/выздоровевших от времени (4 графика).
3) Постройте графики зависимости долей/количества умерших от количества изолированных, протестированных, на карантине. Оцените влияние этих мер. (можно на разных панелях - 6 графиков)
4) Сделайте выводы
   
### Вариант 2
Датасет посвящен мониторингу распространнености (преваленс) диабета в разных странах (broken_diabetes.csv) с временем. Ваша задача - посмотреть как изменилась распространенность диабета в среднем по Европе 
(подсказка: для этого усредните по странам в каждый наблюдаемый год).

1) Подготовьте данные
2) Постройте график зависимости преваленса от года, нанесите на него также усредненные границы доверительных интервалов.
3) Сделайте выводы
   
### Вариант 3
Датасет посвящен предсказанию наступления инфаркта миокарда в зависимости от различных факторов (broken_heart_attack.csv). Ваша задача - посмотреть увеличен ли риск развития инфаркта миокарда у пациентов с ожирением и диабетом в сравнении с пациентами с ожирением.

1) Подготовьте данные (обязательно проверьте не протеворичит ли ИМТ, выставленному диагнозу)
2) Постройте половозрастную пирамиду пациентов
3) Сравните, как распределены частоты наличия инфаркта миокарда у пациентов с ожирением и ожирением, осложненным диабетом
4) Сделайте выводы
