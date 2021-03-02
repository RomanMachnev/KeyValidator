﻿# Отчёт о тестирование "KeyValidator"

## Краткое описание:
02.03.2021-02.03.2021
было проведено "Тестирование установки","Интеграционное тестирование","Функциональное тестирование".
Приложения: KeyValidator.  

На тестирование затрачено: 1час.

В результате тестирования выявлены следующие дефекты:
* [Валидные ключи -невалидные](https://github.com/RomanMachnev/KeyValidator/issues/1)
* [Ключ "2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1" -валидный](https://github.com/RomanMachnev/KeyValidator/issues/2)


## Описание процесса тестирования  
В процессе тестирования использовались следующие артефакты:
* Инструкция по установке OpenJDK 11.
* Руководство использования KeyValidator.

В качестве тестовых данных использовались данные из "Руководство пользования приложения KeyValidator" 

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1  
где OK означает, что ключ валидный, FAIL - невалидный.


 
Тестирование производилось в следующем окружении:
* Wimdows 10.Разрядносность ОП 64.
* Version Java "11.0.10".


