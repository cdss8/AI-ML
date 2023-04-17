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

Лесные пожары (https://archive.ics.uci.edu/ml/datasets/Forest+Fires);

Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality), winequality-red.csv;

Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset), day.csv;

--
--
--




**Laboratory 2**

***Задание 2. Классификаторы***

Написать программу на Python, которая загружает набор данных и выполняет задачи построения бинарных классификаторов, подбора гиперпараметров моделей и анализа качества работы классифицирующих моделей.
1. Выполнить предварительную обработку набора данных.
2. Построить классифицирующие модели с использованием алгоритмов RandomForest, DecisionTree, LogisticRegression. 
3. Визуализировать значения важности признаков для моделей.
4. Напишите короткое заключение о наиболее интересных зависимостях, которые Вы обнаружили в результате выполнения работы.

(https://archive.ics.uci.edu/ml/datasets/Covertype) 

--
--
--


**Laboratory 3**

***Задание 3. Регрессия***

Написать программу на Python, которая обучает четыре регрессионных модели, построенных на наборе с помощью четырёх алгоритмов: линейный регрессор, полиномиальный регрессор, регрессор, основанный на случайном лесе и один из следующих инструментов: Gaussian Process Regression, Support Vector Regression, Gradient Boosting Regressor или AdaBoost Regressor.
Выбрать признаки, использующиеся при обучении, и, если необходимо, выполнить их предобработку. Разделить выборку на обучающую и тестовую. 
 В работе необходимо исследовать работу алгоритмов с разными значениями гиперпараметров. 
Для моделей на основе деревьев вывести значения важности признаков. 
Написать короткий отчет по работе, включив в него программу с комментариями, значения качества моделей (коэффициент детерминации, среднюю квадратичную и среднюю абсолютную ошибки). 
Выбрать наилучшую модель из полученных регрессоров. 

Выборка:
Лесные пожары (https://archive.ics.uci.edu/ml/datasets/Forest+Fires);

Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality) файл winequality-red.csv;   

Качество вина (https://archive.ics.uci.edu/ml/datasets/Wine+Quality) файл winequality-white.csv; 

Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset), файл day.csv; 

Аренда велосипедов (https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset), файл hour.csv;


--
--
--

**Laboratory 4**

***Задание 4 Кластеризация данных***

Напишите программу на Python, которая выполняет алгоритм кластеризации. В качестве набора данных выберите один из тех, которые вы рассмотрели на предыдущих лабораторных работах. 
Для кластеризации выделите два произвольных численных признака. 
При необходимости приведите признаки к стандартному масштабу. 
Используйте следующие алгоритмы кластеризации: K-means, аггломеративная кластеризация и DBScan. Проведите эксперимент по выявлению оптимального количества кластеров, для каждого результата выведите метрику качества (например, коэффициент силуэта или др.), покажите на графике кластеры и центроиды (K-means) для каждого решения и их гиперпараметров. Выберите лучшее сочетание алгоритма и гиперпараметров, сделайте выводы и отразите проделанную работу в отчёте. 

--
--
--

**Laboratory 5**

***Задание 5. Кластеризация данных***

Написать программу на Python, которая обучает нейросетевой классификатор и регрессор, с помощью библиотеки keras. В качестве выборок возьмите варианты, которые Вы исследовали, соответственно, в лабораторной работе №2 и №3. 
Выбрать признаки, использующиеся при обучении, и, если необходимо, выполнить их предобработку. Разделить выборку на обучающую и тестовую. В работе необходимо исследовать работу алгоритмов обучения с разными значениями параметров структуры и обучения (гиперпараметров) сетей и выбрать наилучшие значения последних. 
Написать короткий отчет по работе, включив в него программу с комментариями, значения качества моделей (аналогично лабораторным работам 2 и 3). Выбрать лучшую модель, сравнить производительность с соответствующими лучшими решениями из ранее использованных моделей машинного обучения.

