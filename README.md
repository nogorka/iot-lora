# iot-lora

Часть проекта по интернету вещей. В рамках проекта реализованно:
- [работа датчиков, а также связь датчиков с базовой станцией]();
- [связь между базовой станцией и связь общим веб-сервером и связь между андроид приложением](https://github.com/nogorka/iot-lora);
- [андроид приложение](https://github.com/nodreamistoobig/Lora).

Структура репозитория:

- `server.py` - Flask веб-сервер, бэкэнд для управляющего клиента андроид приложении. 
- `reciver.py` - взаимодействие базовой станции LoRa и flask веб-сервера