# Dmitriy_Gridnev_Yandex_Praktikum_DA_38
В данном репозитории размещены проекты, которые были самостоятельно выполнены в ходе обучения в Яндекс.Практикуме
# Репозиторий учебных проектов из Яндекс Практикум «Аналитик данных»

| Название проекта   | Сферы деятельности | Задачи проекта | Описание проекта | Библиотеки | 
| :----------------- | :------------------| :--------------| :--------------- | :--------- |
| [«Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов»]() | Интернет-сервисы, Стриминговый сервис | На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга. | Сравнение Москвы и Петербурга окружено мифами: Москва — мегаполис, подчинённый жёсткому ритму рабочей недели; Петербург — город своеобразной культуры, непохожий на Москву. Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки были проверены данные, а также, осуществлено сравнение поведение пользователей двух столиц. | pandas |
| [«Исследование надёжности заёмщиков — анализ банковских данных»]() | Банковская сфера, Кредитование | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок |На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Осуществлена лемматизация. |  pandas, pymystem3 |
| [«Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости»]() | Интернет-сервисы, Площадки объявлений | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир |На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость
объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные.
Построены гистограммы, боксплоты, диаграммы рассеивания. |  Python, Pandas, Matplotlib |
| [«Изучение закономерностей, определяющих успешность игр»]()| Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы. | pandas, numpy, seaborn, matplotlib.pyplot, datetime, scipy |
| [«Оптимизация маркетинговых затрат в Яндекс.Афише»]() | Проведен анализ данных от Яндекс.Афиши целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI. | pandas, numpy, seaborn, matplotlib.pyplot, datetime, scipy |
| [«Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста»]() | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провела анализ результатов A/B-теста, построила графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитала статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. | pandas, datetime, matplotlib, numpy, scipy, seaborn |
| [«Анализ пользовательского поведения в мобильном приложении»]() | В данном проекте мной были изучены принципы событийной аналитики. Я построила воронку продаж, исследовала путь пользователей до покупки. Проанализировала результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | pandas, datetime, matplotlib, numpy, scipy, math, seaborn, plotly, statsmodels, proportions_ztest |
| [«Прогнозирование вероятности оттока пользователей для фитнес-центров»]() | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. | pandas, matplotlib, numpy, scipy, seaborn, plotly, sklearn, kmeans, dendrogram, linkage,  statsmodels, proportions_ztest |
| [«Выпускной проект. E-commerce — Анализ товарного ассортимента»]() | Для интернет-магазина товаров для дома «Пока все ещё тут», выявила профили покупателей, сделала полноценный анализ товарного ассортимента. Были категоризированны данные, проанализированы продажи по категориям по временам года. Была проведена сегментация покупателей на основе истории их покупок. Проверка статистических гипотез. [Tableau.]() | pandas, numpy, scipy, sklearn, standardscaler, kmeans, dendrogram, linkage, matplotlib, seaborn , plotly, pymystem3, collections |
| [«Выпускной проект. Проект по АB-тестированию»]() | Используя данные с действиями пользователей, с техническим заданием и несколько вспомогательных датасетами, оценила корректность проведения теста и проанализировала результаты теста. |  pandas, datetime, matplotlib, numpy, scipy, seaborn, plotly, statsmodels, proportions_ztest |
| [«Выпускной проект. SQL – Анализ базы данных сервиса для чтения книг по подписке»]() | Создала коннекцию к базе данных для получения данных. Выполнила запрос и сохранила результат в DataFrame. Провела исследовательский анализ данных. Эти данные помогут сформулировать ценностное предложение для нового продукта. | Инструменты: SQL, пайплайн |
