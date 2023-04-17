# AI-ML

**Laboratory 1**

***Задание 1. Исследовательский анализ и визуализация данных***

Напишите программу на Python, которая загружает набор данных, выполняет исследовательский анализ этих данных и визуализирует набор зависимостей между атрибутами в вариантах, перечисленных ниже, с помощью библиотек matplotlib и sns.
1. Получить описание набора данных и список атрибутов, получить количество пропущенных значений для каждого атрибута.
2. Обработка отсутствующих значений (удаление строк/удаление атрибутов/изменение значений)
3. Постройте pairplot для пяти признаков из набора данных.
Добавьте легенду и подпись для каждого изображения в следующих задачах.
4. Выберите не менее двух атрибутов с определенным распределением значений и покажите это распределение гистограммами hist и kdeplot, jointplot
5. Выберите некоторые из атрибутов и просмотрите корреляцию между ними в виде тепловой карты. Затем создайте тепловую карту, показывающую только высокие значения прямой и обратной корреляции.
6. Выберите три атрибута (с определенным распределением значений), целевую переменную (категориальную) и отобразите для них диаграммы с областями (блочная диаграмма).
7. Визуализируйте некоторую статистику для различных атрибутов, используя следующие инструменты: Violinplot, Countplot, FacetGrid, Stripplot, Swarmplot, Catplot, Pie.
Напишите краткий обзор наиболее интересных взаимосвязей, которые вы обнаружили в данных.

Выборка:
Лесные пожары (https://archive.ics.uci.edu/ml/datasets/Forest+Fires );
Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality ); winequality-red.csv
Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset ), day.csv;







**Laboratory 2**

***Задание 2. Классификаторы***

Написать программу на Python, которая загружает набор данных и выполняет задачи построения бинарных классификаторов, подбора гиперпараметров моделей и анализа качества работы классифицирующих моделей.
1. Выполнить предварительную обработку набора данных.
2. Построить классифицирующие модели с использованием алгоритмов RandomForest, DecisionTree, LogisticRegression. 
3. Визуализировать значения важности признаков для моделей.
4. Напишите короткое заключение о наиболее интересных зависимостях, которые Вы обнаружили в результате выполнения работы.

(https://archive.ics.uci.edu/ml/datasets/Covertype) 




**Laboratory 2**

***Задание 3. Регрессия***

Написать программу на Python, которая обучает четыре регрессионных модели, построенных на наборе с помощью четырёх алгоритмов: линейный регрессор, полиномиальный регрессор, регрессор, основанный на случайном лесе и один из следующих инструментов: Gaussian Process Regression, Support Vector Regression, Gradient Boosting Regressor или AdaBoost Regressor.
Выбрать признаки, использующиеся при обучении, и, если необходимо, выполнить их предобработку. Разделить выборку на обучающую и тестовую. 
 В работе необходимо исследовать работу алгоритмов с разными значениями гиперпараметров. 
Для моделей на основе деревьев вывести значения важности признаков. 
Написать короткий отчет по работе, включив в него программу с комментариями, значения качества моделей (коэффициент детерминации, среднюю квадратичную и среднюю абсолютную ошибки). 
Выбрать наилучшую модель из полученных регрессоров. 


Выборка:
Лесные пожары (https://archive.ics.uci.edu/ml/datasets/Forest+Fires), предсказываемое значение – площадь пожара (Area); 
Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality) предсказываемое значение – качество (Quality), файл winequality-red.csv; 
Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality) предсказываемое значение – качество (Quality), файл winequality-white.csv; 
Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset), предсказываемое значение – количество аренд велосипедов в сутки(Area), файл day.csv; 
Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset), предсказываемое значение – количество аренд велосипедов в час(Area), файл hour.csv;
