# Описание проекта "Антитоксичная модель"

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.<br>

Необходимо научить модель классифицировать комментарии на позитивные и негативные. В распоряжении имеется набор данных (тексты на английском языке) с разметкой о токсичности правок.

## Данные

160 тысяч комментариев с разметкой о токсичности 

## Задача

Подготовить сырые данные, обучить на них модели, протестировать лучшую.

## Используемые библиотеки
*pandas*, *numpy*, *matplotlib*, *seaborn*, *sklearn*, *tensorflow*, *re*, *torch*, *transformers*, *imblearn*, *nltk*, *lightgbm*, *catboost*
