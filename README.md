# **Проект прогнозирования временных рядов (акции Амазона)**
## Стек:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?logo=seaborn&logoColor=white&style=for-the-badge)
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0CEEKtXoRAs03ZPC660df0vQmFMTI49kdhA&s" alt="Statsmodels" width="150">
<img src="
https://repository-images.githubusercontent.com/400528139/1af59e40-a8c4-4791-8450-1736829ba25c" alt="ETNA" width="60">
<img src="https://media.licdn.com/dms/image/C5612AQGOX3Bpav4kMg/article-cover_image-shrink_600_2000/0/1602915913499?e=2147483647&v=beta&t=diGK4nPQDE0NgOHtPthU6-LMQ-a5C60x1q16HDCEIv0" alt="Catboost" width="100">
## Главными целями данного исследования являются:

1.   Анализ методов прогнозирования временных рядов, используя библиотеки Statsmodels, Sklearn, Catboost и ETNA
2.   Определение методов, имеющих наименьшее значение метрик MAE, MAPE, RMSE
_______
## **Входные данные** 
_____
Данные выгружены с платформы NASDAQ с 2023-04-28 по 2024-04-26 Скачать данные можно по ссылке https://www.nasdaq.com/market-activity/stocks/amgn
### **Описание полей датафрейма**

*   Open - Цена, по которой начинается торговля скриптом в начале торговой сессии.
*   Low— самая низкая цена, по которой торговался скрипт во время торговой сессии.
*   High — самая высокая цена, по которой торговался скрипт во время торговой сессии.
*   Close/Last — Цена, по которой торговался скрипт в конце последней торговой сессии.
*   Volume—количество проданных акций
*   Date—дата торговой сессии
________
## **Используемые методы для прогнозирования**
* Линейная регрессия с разными вариантами признаков
* Дерево решений
* Случайный лес
* Градиентный бустинг(Catboost)
* Разные варианты использования экспоненциального сглаживания(Линейный тренд Хольта, Экспоненциальный тренд, а также два варианта использования метода Хольта-Винтерса: additive-additive-seasonal и additive-multiplicative-seasonal)
* Наивная модель
* Профет
* ARIMA
