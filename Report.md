# Отчёт о тестировании Credit Card Number Validator

## Краткое описание
01.04.2021 - 02.04.2021гг. было проведено функциональное модульное тестирование валидации номера банковской карты.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:

- [При вводе в строку кода номера карты номера American Express приложение выдает "Result is fail"](https://github.com/TLyzlova/Credit-card-test/issues/1)

- [При вводе в строку кода номера карты номера Diner Club приложение выдает "Result is fail"](https://github.com/TLyzlova/Credit-card-test/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

- [Тест-кейс](https://docs.google.com/spreadsheets/d/1jcGT9YU9ixQXsOdN9whI5XYS6z8Pb6frv5mwblw8O3w/edit?usp=sharing)


В качестве тестовых данных использовались данные с сайта:

[CreditCardGenerator.in](https://creditcardgenerator.in/) 



- карта Visa номер 4384081819330000

- карта American Express номер 377248987703444

- карта Diner Club номер  62526295638287871


Тестирование производилось в следующем окружении:

- Windows 10 64 bit 
- IntelliJ Idea version 11.0.10+8-b1145.96 amd64 
