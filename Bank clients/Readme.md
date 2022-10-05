# Отток клиентов

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

**Pflfxf** -  спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. 

Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Стек:** `numpy` `pandas` `matplotlib` `sklearn` `StandardScaler`

### Вывод

Таким образом, лучшей моделью для прогноза, уйдёт клиент из банка в ближайшее время или нет, является модель "Случайный лес" с параметрами max_depth=11, n_estimators=41, полученная путем увеличения выборки для устранения дисбаланса классов.