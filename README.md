# Project Arduino(C++), Android(Java) and Python
Уведомление человека об изменении температуры в помещении по сравнению с нормой (в архивах, хранилищах овощей и т.п.)
## Структура
- code_zip - архивы с кодом (распаковать люибым архиватором)
- docs - документация
## Инструкция 
### Arduino(C++)
1. Установить [Arduino IDE](https://www.arduino.cc/en/Main/Software).
2. Распаковать /code_zip/ArduinoSensorCKFH_Stock.zip.
3. Запустить Arduino IDE и окрыть /NANO/MAIN/MainProject.ino (Файл -> Открыть -> выбрать в директории /NANO/MAIN).
4. Выбрать в Arduino IDE тип платы Nano и подключить плату Arduino Nano с помощью USB порта.
   Примечание: От плата Arduino Nano должны быть отключены все утройства кроме USB.
5. Настроить порт и выбрать его в Arduino IDE.
6. В меню Arduino IDE выбрать Скетч -> Загрузка.
### Android(Java)
1. Установить [Android Studio](https://developer.android.com/studio?hl=ru).
2. Установить JDK Suite. 
3. Распаковать /code_zip/ArduinoSensorCKFH_Android.zip.
4. Запустить Android Studio.
5. Открыть ранее распакованную директорию (возможно, понадобится донастройка конфигурации под Application).
6. Подключить Android смартфон по USB, включить на смартфоне режим разработчика.
7. Запустить проект (Run).
8. При необходимости собрать проект в .pak.
### Python
1. Установить [PyCharm Community](https://www.jetbrains.com/pycharm/) и интерпретатор Python 3.0 и выше.
2. Распаковать /code_zip/ArduinoSensorCKFH_Python.zip.
3. Запустить PyCharm Community.
4. В меню PyCharm Community выбрать Файл -> Открыть и открыть ранее распакованную директорию
5. Запустить проект Run -> Run 'AppMain'
