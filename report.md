# Отчёт о тестировании KeyValidator

## Краткое описание

10 июля 2021 - 10 июля 2021 было проведено Функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 00:30 ч.

В результате тестирования выявлены следующие дефекты:
* [Результат FAIL при вводе валидного ключа](https://github.com/cromax-max/KeyValidator/issues/1#issue-941230929)
* [Результат OK при вводе невалидного ключа](https://github.com/cromax-max/KeyValidator/issues/2#issue-941231873)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F-%D0%BF%D0%BE-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B5-openjdk11)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator)

В качестве тестовых данных использовались данные:

Валидные ключи:

* [Ключи для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8)

Тестирование производилось в следующем окружении:
* Windows10 (64-bit)
* openjdk version "11.0.11" 2021-04-20  
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)  
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)  