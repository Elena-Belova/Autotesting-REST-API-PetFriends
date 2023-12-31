# Проверка функциональности API сервиса
Тестирование REST API веб-приложения "Pet Friends"

* [Пользовательские сценарии](https://github.com/Elena-Belova/Autotesting-REST-API-PetFriends/blob/cbf059938d47277cc532c68cbe75675ae9902ef0/API%20PetF%20UseC.pdf) в формате тест-кейсов

* [Тест-кейсы для проверки метода GET](https://github.com/Elena-Belova/Autotesting-REST-API-PetFriends/blob/f9073c357014552cca432b365e09575b7bfaf677/API%20PetF%20GET.pdf)

* [Тест-кейсы для проверки метода POST](https://github.com/Elena-Belova/Autotesting-REST-API-PetFriends/blob/f9073c357014552cca432b365e09575b7bfaf677/API%20PetF%20POST.pdf)

* [Тест-кейсы для проверки метода PUT](https://github.com/Elena-Belova/Autotesting-REST-API-PetFriends/blob/f9073c357014552cca432b365e09575b7bfaf677/API%20PetF%20PUT.pdf)

* [Тест-кейсы для проверки метода DELETE](https://github.com/Elena-Belova/Autotesting-REST-API-PetFriends/blob/f9073c357014552cca432b365e09575b7bfaf677/API%20PetF%20DELETE.pdf)

**Структура:**

* Директория `/tests` содержит:
  * файл с тестами `test_pet_friends.py`
  * в `/tests/images` - изображения, используемые в тестах

* Файл `settings.py` содержит информацию о валидных/невалидных данных пользователя
  
* Файл `api.py` является библиотекой для взаимодействия с REST API сервиса веб-приложения Pet Friends.
  * Библиотека `api` реализована в классе, что соответствует принципам ООП и предоставляет удобные методы для работы с API.
При инициализации библиотеки объявляется переменная `base_url`, которая используется при формировании url для запросов.
Каждый метод в библиотеке имеет описание функциональности.
---


