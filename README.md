# Data Science проекты

В репозитории хранятся готовые варианты проектов, выполненных в ноутбуке Jupiter Notebook.  
Источники данных (использованные в исследованиях файлы .csv с датасетами) не приложены.  
Для правильного отображения содержимого, проекты рекомендуется просматривать при помощи [External viewer](https://nbviewer.jupyter.org/).

| №   | **Название проекта**              | **Описание**                                                                     | Навыки и инструменты                            |
| :---| :-------------------------------- |:---------------------------------------------------------------------------------|:------------------------------------------------|
| 1   | [Исследование надёжности заёмщиков](https://github.com/AlishaMv/Data_Science_Projects/tree/main/borrower_reliability_research) | На основе статистики о платёжеспособности клиентов проведено исследование о влиянии семейного положения и количества детей клиента на факт возврата кредита в срок | `Предобработка данных` `Лемматизация` `Категоризация` `Python` `Pandas` `PyMystem3` |
| 2 | [Исследование объявлений о продаже квартир](https://github.com/AlishaMv/Data_Science_Projects/tree/main/spb_real_estate_eda) | Исследовать данные сервиса Яндекс.Недвижимость и определить какие параметры объектов недвижимости влияют на формирование цен на них| `Предобработка данных` `Исследовательский АД` `Визуализация` `Python` `Pandas` `Matplotlib` |
| 3 | [Определение перспективного тарифа для телеком компании](https://github.com/AlishaMv/Data_Science_Projects/tree/main/optimal_tariff_telecom) | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и осуществить поиск оптимального тарифного плана | `Предобработка данных` `Исследовательский АД` `Описательная статистика` `Проверка статистических гипотез` `Machine Learning` `Python` `Pandas` `Matplotlib` `Numpy` `SciPy` |
| 4 | [Выявление закономерностей, определяющих успешность компьютерных игр](https://github.com/AlishaMv/Data_Science_Projects/tree/main/games_eda) | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры  | `Предобработка данных` `Описательная статистика` `Исследовательский АД` `Проверка статистических гипотез` `Python` `Pandas` `Numpy` `SciPy` `Matplotlib` |
| 5 | [Рекомендация тарифов мобильной связи](https://github.com/AlishaMv/Data_Science_Projects/tree/main/tariff_recommend_system) | Используя данные о поведении клиентов, которые уже перешли на тарифы мобильной связи, построить модель для задачи классификации, которая выберет наилучший тариф с использованием имеющихся данных о клиентах и предложит его пользователю в качестве оптимального и самого выгодного | `Python` `Machine Learning` `Pandas` `Matplotlib` `Numpy` `Sklearn` |
| 6 | [Выбор региона для разработки новых нефтяных месторождений](https://github.com/AlishaMv/Data_Science_Projects/tree/main/oil_well_loc) | Необходимо построить модель для предсказания объёма запасов в новых скважинах, проанализировать возможную прибыль и риски техникой Bootstrap. На основании исследований порекомендовать регион к освоению. | `Предобработка данных` `Python` `Machine Learning` `Pandas` `Matplotlib` `Numpy` `Sklearn` `SciPy` `seaborn` `A/B-тестирование` `Bootstrap` `Gradient Boosting` `LinearRegression` |
| 7 | [Разработка алгоритма защиты персональных данных клиентов](https://github.com/AlishaMv/Data_Science_Projects/tree/main/personal_data_protection) | Методом преобразования данных защитить личную информацию клиентов страховой компании | `Python` `Pandas` `Numpy` `SciPy` `Matplotlib` `Sklearn` |
| 8 | [Прогнозирование количества заказов такси](https://github.com/AlishaMv/Data_Science_Projects/tree/main/taxi_time_series) | Проанализировать исторические данные о заказах такси в аэропортах и обучить модель для предсказания количества заказов такси на следующий час | `Python` `Pandas` `Machine Learning` `Sklearn` `Numpy` `Matplotlib` `Catboost` `LightGBM` `LinearRegression` `DecisionTree` `RandomForest` `Catboost` `LightGBM` `LinearRegression` `DecisionTree` `RandomForest` `Time Series` |
| 9 | [Прогнозирование оттока клиентов из банка](https://github.com/AlishaMv/Data_Science_Projects/tree/main/churn_clients_bank) | На основе предоставленных исторических данных о клиентах банка, необходимо спрогнозировать вероятность ухода клиента из банка в ближайшее время | `Machine Learning` `Python` `Pandas` `Sklearn` `Numpy` `Matplotlib` `Upsampling` `Downsampling` `One-Hot Encoding` `GridSearchCV` |
| 10 | [Предсказание стоимости автомобиля](https://github.com/AlishaMv/Data_Science_Projects/tree/main/auto_price_prediction) | Обучить модель для быстрого предсказания рыночной стоимости автомобиля с пробегом (алгоритм будет использоваться в мобильном приложении)| `Python` `Machine Learning` `Pandas` `Sklearn` `Numpy` `Matplotlib` `Catboost` `LightGBM` `LinearRegression` `DecisionTree` `Ordinal Encoding` |
| 11 | [Классификация комментариев по тональности](https://github.com/AlishaMv/Data_Science_Projects/tree/main/toxic_comments) | Необходимо ускорить модерацию комментариев в сообществе, автоматизировав оценку их токсичности, обучив модель классифицировать комментарии на позитивные и негативные | `Предобработка данных` `Machine Learning` `Feature engineering` `Pandas` `Sklearn` `NLTK` `Numpy` `LinearRegression` `LogisticRegression` `BERT` `LinearSVC` `Токенизация` `Лемматизация`|
| 12 | [Предсказание коэффициента восстановления золота из золотосодержащей руды](https://github.com/AlishaMv/Data_Science_Projects/tree/main/gold_prediction) | Необходимо разработать модель, способную предсказывать коэффициент восстановления золота из золотосодержащей руды. | `Промышленное моделирование` `Предобработка данных` `Machine Learning` `Python` `Pandas` `Sklearn` `Numpy` `LinearRegression` `RandomForest` `Cross-validation`|
| 13 | [Исследование спроса на рейсы авиакомпании (+SQL)]() | В качестве аналитика авиакомпании, попытаться понять предпочтения пользователей, покупающих билеты на разные направления |  `SQL` `Python` `Исследовательский АД` `Pandas` `Matplotlib` `Numpy` `Plotly` |

Alina Medvedeva medvedeva.alisha@gmail.com
