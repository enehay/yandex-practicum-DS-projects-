# Описание задачи

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Необходимо построить модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.

Дополнительно необходимо измерить AUC-ROC, сравнить её значение с F1-мерой.


# Навыки и инструменты

Python, pandas, numpy, matplotlib, sklearn

# Вывод

На основе предоставленых исторических данных о поведении клиентов и расторжении договоров с банком, спрогнозированно, уйдёт клиент из банка в ближайшее время или нет. Исследован баланс классов, изучены модели без учёта дисбаланса, применено несколько способов борьбы с дисбалансом, удалось достичь F1-меры не менее 0.49, исследована метрика AUC-ROC.


