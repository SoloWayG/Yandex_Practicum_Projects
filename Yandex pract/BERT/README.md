# Описание проекта
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

Постройте модель со значением метрики качества F1 не меньше 0.75. 


Выводы:

По итогу выполнения проекта, были получены эмбеддинги от BERT, на основе которых были созданы модели обучения предсказания токсичности комментариев.

f1 score Логистической Регресси на тесте 0.8428

f1 score CatBoost на тесте 0.8358

f1 score RandomForest на тесте 0.808

В данном решении результат ЛогРегрессии выше, чем CatBoost. Это связанно с тем, что подбор гипперпараметров весьма времязатратное занятие. И это совсем не плохо, данная ситуация доказывает то, что не существует одного лучшего решения на все случаи, и иногда намного быстрее использовать не самый мощный инструмент, но получить отличный результат!

