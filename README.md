# Weather service

Сервис должен:
- Быть написан на NodeJS, база - PostgreSQL.
- Получать данные о погоде в реальном времени с использованием [API Tomorrow.io](https://docs.tomorrow.io/reference/realtime-weather). Интервал поллинга API внутри сервиса - 1 минута.
- Предоставлять публичный Websocket API со следующими эндпоинтами:
  - Получение погоды в реальном времени. Параметры эндпоинта:
    - Название города
  - Получение погоды за выбранный интервал времени с возможностью агрегации среднего значения. Параметры эндпоинта:
    - Название города
    - Интервал "от" и "до"
    - Окно агрегации. Возможные значения:
      - Без агрегации (1 минута)
      - 5 минут
      - 30 минут
      - 60 минут
- При разработке сервиса можно использовать любые open-source библиотеки и пакеты из npm
     

Готовое решение предоставить в виде ссылки на публичный Github-репозиторий HRу.
Вопросы по тестовому заданию можно адресовать в Telegram: [@wainpc](https://t.me/wainpc) 
