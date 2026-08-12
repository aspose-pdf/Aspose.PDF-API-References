---
title: "System::Globalization::GregorianCalendar класс"
linktitle: "GregorianCalendar"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::GregorianCalendar класс. Григорианский календарь. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.globalization/gregoriancalendar/
---
## GregorianCalendar class


Григорианский календарь. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Информация RTTI. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Получает тип алгоритма. |
| virtual [get_CalendarType](./get_calendartype/)() const | Получает тип григорианского календаря. |
| [get_Eras](./get_eras/)() const override | Получает список эпох, существующих в календаре. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Максимальная точка времени, поддерживаемая календарём. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Минимальная точка времени, поддерживаемая календарём. |
| [GetDayOfMonth](./getdayofmonth/)(DateTime) const override | Получает день месяца для указанной временной точки. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Получает день недели для указанной временной точки. |
| [GetDayOfYear](./getdayofyear/)(DateTime) const override | Получает день года для указанной временной точки. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Получает количество дней в конкретном месяце. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Получает количество дней в конкретном месяце. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Получает количество дней в конкретном году. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Получает количество дней в конкретном году. |
| static [GetDefaultInstance](./getdefaultinstance/)() | Получает экземпляр календаря григорианского по умолчанию. |
| [GetEra](./getera/)(DateTime) const override | Получает эпоху для указанной временной точки. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Получает високосный месяц для указанного года. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Получает високосный месяц для указанного года. |
| [GetMonth](./getmonth/)(DateTime) const override | Получает месяц для указанной временной точки. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Получает количество месяцев в указанном году. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Информация RTTI. |
| [GetYear](./getyear/)(DateTime) const override | Получает год для указанного момента времени. |
| [GregorianCalendar](./gregoriancalendar/)(GregorianCalendarTypes) | Создаёт конкретный григорианский календарь. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Проверяет, является ли день високосным. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Проверяет, является ли день високосным. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Проверяет, является ли месяц високосным. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Проверяет, является ли месяц високосным. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Проверяет, является ли год високосным. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Проверяет, является ли год високосным. |
| virtual [set_CalendarType](./set_calendartype/)(GregorianCalendarTypes) | Устанавливает тип григорианского календаря. |
| [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [ADEra](./adera/) | Текущая эра. |
## См. также

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
