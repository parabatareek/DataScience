# Цель проекта #
Построение модели прогнозирования оттока абонентов.

# Инструменты #
1. pandas
2. seaborn
3. numpy
4. matplotlib
5. sklearn
6. xgboost
7. lightgbm
8. catboost
9. plotly.express

# Описание данных #
Данные состоят из файлов, полученных из разных источников:

- `contract.csv` — информация о договоре;
- `personal.csv` — персональные данные клиента;
- `internet.csv` — информация об интернет-услугах;
- `phone.csv` — информация об услугах телефонии.

Во всех файлах столбец `customerID` содержит код клиента.

Информация о договорах актуальна на 1 февраля 2020.