# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

24/02/2020 - 24/02/2020 было проведено ручное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:


## Описание процесса тестирования

План тестирования:
1. Открыть Credit Card Number Validator в IntelliJ IDEA.
2. Внести тестовые данные в строку String number = "";

Необходимо проверить, что: 
1. Функциональность валидации номера банковской карты работает.

В качестве тестовых данных использовались данные, взятые с ресурса Credit Card Number Generator & Validator (https://www.freeformatter.com/credit-card-number-generator-validator.html):

Валидные номера:
* 4539692950092268
* 4532441711849049959
* 5130620099465541
* 30049947516895

Невалидные номера:
* 777777777777777777
* 777
* aaaa
* /отсутствие данных/

Тестирование производилось в следующем окружении:
* Windows 10 Pro, x64
* openjdk version "11.0.6" 2020-01-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
