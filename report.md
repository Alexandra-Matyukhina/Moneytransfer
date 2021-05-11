# Отчёт о тестировании <Название приложения>

## Краткое описание

<2021.05.11 at 9:00 PM> - <2021.05.11 at 9:40> было проведено тестирование методом White Box приложения **MoneyTransfer**.

На тестирование затрачено: <40 минут>

В результате тестирования выявлены следующие дефекты:
* [Отрицательное значение при сложении положительных чисел типа данных int](https://github.com/Alexandra-Matyukhina/Moneytransfer/issues/1#issue-888239412)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* IntelliJ IDEA Community Edition
* Код приложения **MoneyTransfer**

В качестве тестовых данных использовался код приложения **MoneyTransfer**:
* int balance = 2_000_000_000;
  int transfer = 500_000_000;
  int total = balance + transfer; **Exp.result is 2_500_000_000**

Тестирование производилось в следующем окружении:
* Устройство: Microsoft Surface Laptop 3
* Windows 10
* AdoptOpenJDK JDK with Hotspot 11.0.10+9 (x64)
* IntelliJ IDEA 2021.1.1 (Community Edition), Runtime version: 11.0.10+9-b1341.41 amd64