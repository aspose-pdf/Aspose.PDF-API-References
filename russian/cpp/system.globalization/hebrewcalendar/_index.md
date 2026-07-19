---
title: "System::Globalization::HebrewCalendar class"
linktitle: "HebrewCalendar"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::HebrewCalendar class. Еврейский календарь. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.globalization/hebrewcalendar/
---
## HebrewCalendar class


Еврейский календарь. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HebrewCalendar : public System::Globalization::Calendar
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Информация RTTI. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Получает тип алгоритма. |
| [get_Eras](./get_eras/)() const override | Получает список эпох, существующих в календаре. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Максимальная точка времени, поддерживаемая календарём. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Минимальная точка времени, поддерживаемая календарём. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Получает день недели для указанной временной точки. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Получает количество дней в конкретном месяце. |
| [GetEra](./getera/)(DateTime) const override | Получает эпоху для указанной временной точки. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Получает високосный месяц для указанного года. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Информация RTTI. |
| [GetMonth](./getmonth/)(DateTime) const override | Получает месяц для указанной временной точки. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Получает количество месяцев в указанном году. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Получает количество месяцев в указанном году. |
| [HebrewCalendar](./hebrewcalendar/)() | Конструктор. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Проверяет, является ли день високосным. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Проверяет, является ли день високосным. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Проверяет, является ли месяц високосным. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Проверяет, является ли месяц високосным. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Проверяет, является ли год високосным. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Проверяет, является ли год високосным. |
| [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Устанавливает последний год, который может быть представлен двухзначным. |
| [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [HebrewEra](./hebrewera/) | Текущая еврейская эра. |
## См. также

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
