SQL запросы для анализа результатов маркетинговой кампании

Банк разместил рекламу в Яндекс Директе в рамках маркетинговой акции "бесплатное обслуживание счёта в первый год"
Есть база данных:

event_datetime: время события, только 2020 год

event_id: идентификатор события, первичный ключ

user_id: идентификатор посетителя (один пользователь может несколько раз заходить на сайт, в том числе и в течение дня, в том числе с разных городов). Так же посещения могут быть уже после открытия счета

event_name: название события (Посещение сайта или Открытие счета). Для упрощения - счет может открыться только после посещения сайта, и каждый посетитель может открыть только один счет

city: город

cost: расчетная стоимость привлечения посетителя на сайт
