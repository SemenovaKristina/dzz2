# Отчёт о тестировании Precision

## Краткое описание

13.08.2021 - 13.08.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 0,5 часа

В результате тестирования выявлены следующие дефекты:
* [IntelliJ IDEA. Неправильно считается totalBonus при сложении переменных regularBonus и specialBonus](https://github.com/SemenovaKristina/dzz2/issues/1)


## Описание процесса тестирования


[В качестве тестовых данных использовались данные](https://i.imgur.com/0EMJXPU.png) :
* double regularBonus = 0.3
* double specialBonus = 0.6
* double totalBonus = regularBonus + specialBonus

Тестирование производилось в следующем окружении:
* Windows 10 x64
* Java version "11.0.11"