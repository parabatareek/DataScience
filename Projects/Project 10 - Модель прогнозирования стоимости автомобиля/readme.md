# Цель проекта #    
Создание модели, прогнозирующей рыночную стоимость автомобиля

# Инструменты #
1. math
2. time
3. pandas
4. seaborn
5. matplotlib
6. plotly_express
7. sklearn
8. catboost
9. xgboost
10. lightgbm

# Описание данных #
Признаки:
    * DateCrawled — дата скачивания анкеты из базы
    * VehicleType — тип автомобильного кузова
    * RegistrationYear — год регистрации автомобиля
    * Gearbox — тип коробки передач
    * Power — мощность (л. с.)
    * Model — модель автомобиля
    * Kilometer — пробег (км)
    * RegistrationMonth — месяц регистрации автомобиля
    * FuelType — тип топлива
    * Brand — марка автомобиля
    * NotRepaired — была машина в ремонте или нет
    * DateCreated — дата создания анкеты
    * NumberOfPictures — количество фотографий автомобиля
    * PostalCode — почтовый индекс владельца анкеты (пользователя)
    * LastSeen — дата последней активности пользователя
Целевой признак:
    * Price — цена (евро)
