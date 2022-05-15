# vk-weather-bot
# first step: install python modules
# pip install translate
# pip install pyowm
# pip install vk-api
# pip install Pillow
# second step: edit code
# create account in openweathermap.org and add your OWM key on code
# create account in vk.com and add your loggin and password on code
# copy id person account or group in vk and add their on code
# last step: run code, well done!


Скачиваем проект к себе на компьютер Устанавливаем необходимые модули:


- Pillow==8.4.0
- pyowm==3.3.0
- vk-api==11.9.7
- translate==3.6.1 (у библеотеки ограниченное количество переводов, в проекте по умолчанию выключен)


Они находятся в файле requirements.txt

Установка: pip install -r ./requirements.txt

Регистрируемся на сайте OWM и получаем ключ (https://openweathermap.org)

Добавте полученный ключ в код

В коде измените город для которого хотите получать прогноз погоды

Изменяем остальной код под свои нужды

Запускаем, не работет, ура!
