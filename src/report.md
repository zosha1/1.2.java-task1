# Отчёт о тестировании Money Transfer

## Краткое описание

12.05.2021 - 12.05.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 0,25 часа

В результате тестирования выявлены следующие дефекты:
* [Баланс клиента после пополнения счета стал отрицательным.](https://github.com/zosha1/1.2.java-task1/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные:
* текущий баланс счёта клиента - 2 000 000 000
* сумма перевода - 500 000 000

**Ожидаемый результат:** 
Баланс клиента - 2 500 000 000.

Тестирование производилось в следующем окружении:
* MacBook Air, macOS
* Java 11
* IntelliJ IDEA