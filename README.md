Программный код виртуального устройства содержащего погодные и астрономические данные для контроллера WirenBoard.
Данные виртуального устройства:
- Температура
- Ощущается как
- Скорость ветра
- Общие погодные условия
- Время загрузки данных
- Время рассвета
- Время заката

Для добавления виртуального устройства скопируйте программный код из файла weather.js в раздел "Правила" на web интерфейсе контроллера (создав новое правило).
Файлы weather.py / sunset_sunrise.py скопируйте на контроллер в директорию /root/script/python (или любую другую при этом изменив путь к ним в правиле weather.js на контроллере).
Для погодных данных необходим ключ Yandex Weathe Api, ключ Яндекс выдает бесплатно (с ограничением не более 30 запросов в день) https://yandex.ru/pogoda/b2b/smarthome.

![image](https://github.com/user-attachments/assets/615b31ac-5a4d-47f0-b9c8-53488f096d7a)
