# Отчёт о тестировании KeyValidator задача №2

## Краткое описание

24.07.23 - 27.07.23 было проведено <перечисление видов тестирование> приложения *KeyValidator*.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Тестовое задание: [Задача №2 - KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/README.md) 
* Инструкция по установке [OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* Руководство использования [KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Для тестирования установки *OpenJDK11*, в качестве тестовых данных использовалась ["Инструкция по установке OpenJDK11"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md).

Для тестирования запуска приложения *KeyValidator*, в качестве тестовых данных использовалось ["Руководство использования KeyValidator"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md).

При тестировании приложения *KeyValidator*, в качестве тестовых данных использовались данные ["Ключи для проверки"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

*Валидные ключи*:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 - FAIL
* b295bc63-9f03-3b4b-af80-969b39f8c262 - OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317 - FAIL
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - OK

*Невалидные ключи*:
* 18252235-78e0-44a5-8720-556f0c7da17a - FAIL
* e66075b6-ddad-445e-baf6-161b3289522b - FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca - FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42 - FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - OK

Тестирование производилось в следующем окружении:
* Linux Ubuntu 21.04 amd64;
* OpenJDK 11.0.19;
* IntelliJ IDEA 2021.3.2 (Community Edition).