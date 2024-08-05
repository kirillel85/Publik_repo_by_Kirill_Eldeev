```
├── README.md          <- README для разработчиков, использующих этот проект
├── data
│   ├── raw data       <- Исходные сырые данные
│   ├── processed      <- Обработанные данные
│   └── interim        <- Преобразованные промежуточные данные
│
├── docs               <- Документы для проекта 
│
├── notebooks 
│   ├── raw nt         <- Коды для выгрузки сырых данных
|   ├── data line      <- Линии данных для БД
│   ├── processing     <- Коды для обработанных данных
│   └── sandbox        <- Песочница 
|
|    <- Ноутбуки Jupyter. Naming convention is a number (for ordering),
|    the creator's initials, and a short `-` delimited description, e.g.
|    `1.0-jqp-initial-data-exploration`.
│
├── references         <- Словари данных, руководства и другие материалы.
│
├── requirements-linux.txt   <- `pip3 freeze > requirements-linux.txt`
|                         создание файла со списком библиотек
|                         `pip install -r requirements.txt`
|                         установка всех библиотек из файла со списком библиотек
```