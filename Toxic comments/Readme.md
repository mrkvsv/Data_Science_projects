# Предсказание позитивных и негативных комментариев пользователей интернет-магазина.

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других.
Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

**Задача** -  обучить модель классифицировать комментарии на позитивные и негативные.

**Стек:** `numpy` `sklearn` `spacy` `torch` `BERT`

### Вывод

Таким образом, нами подготовлены данные и обучены различные модели. 
Лучшей моделью по качеству метрики F1 стала LogisticRegression, обученная на признаках, подготовленных BERT (unitary/toxic-bert), с параметрами: C = 1, penalty = 'l2', и порогом классификации 0.489, показавшая на тестовой выборке значение F1 равное 0.95.
