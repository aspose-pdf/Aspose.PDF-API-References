---
title: "System::Globalization::Calendar класс"
linktitle: "Calendar"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::Calendar класс. Календарь, определяющий способ обработки, вычисления, форматирования дат и т.д. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.globalization/calendar/
---
## Calendar class


[Calendar](./) which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Calendar : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AddDays](./adddays/)(DateTime, int) const | Добавляет дни к моменту времени. |
| virtual [AddHours](./addhours/)(DateTime, int) const | Добавляет часы к моменту времени. |
| virtual [AddMilliseconds](./addmilliseconds/)(DateTime, double) const | Добавляет миллисекунды к моменту времени. |
| virtual [AddMinutes](./addminutes/)(DateTime, int) const | Добавляет минуты к моменту времени. |
| virtual [AddMonths](./addmonths/)(DateTime, int) const | Добавляет месяцы к моменту времени. |
| virtual [AddSeconds](./addseconds/)(DateTime, int) const | Добавляет секунды к моменту времени. |
| virtual [AddWeeks](./addweeks/)(DateTime, int) const | Добавляет недели к моменту времени. |
| virtual [AddYears](./addyears/)(DateTime, int) const | Добавляет годы к моменту времени. |
| [Calendar](./calendar/)(const Calendar\&) | Информация RTTI. |
| virtual [get_AlgorithmType](./get_algorithmtype/)() const | Получает тип алгоритма. |
| [get_CurrentEra](./get_currentera/)() const | Получает индекс текущей эры. |
| [get_CurrentEraValue](./get_currenteravalue/)() const | Получает значение текущей эры. |
| virtual [get_Eras](./get_eras/)() const | Получает список эпох, существующих в календаре. |
| virtual [get_ID](./get_id/)() const | Получает идентификатор календаря. |
| [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли календарь только для чтения. |
| virtual [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Максимальная точка времени, поддерживаемая календарём. |
| virtual [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Минимальная точка времени, поддерживаемая календарём. |
| virtual [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Получает последний год, который может быть представлен двухзначным. |
| virtual [GetDayOfMonth](./getdayofmonth/)(DateTime) const | Получает день месяца для указанной временной точки. |
| virtual [GetDayOfWeek](./getdayofweek/)(DateTime) const | Получает день недели для указанной временной точки. |
| virtual [GetDayOfYear](./getdayofyear/)(DateTime) const | Получает день года для указанной временной точки. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Получает количество дней в конкретном месяце. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Получает количество дней в конкретном месяце. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Получает количество дней в конкретном году. |
| virtual [GetDaysInYear](./getdaysinyear/)(int, int) const | Получает количество дней в конкретном году. |
| virtual [GetEra](./getera/)(DateTime) const | Получает эпоху для указанной временной точки. |
| virtual [GetHour](./gethour/)(DateTime) const | Получает часы для указанного момента времени. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Получает високосный месяц для указанного года. |
| virtual [GetLeapMonth](./getleapmonth/)(int, int) const | Получает високосный месяц для указанного года. |
| virtual [GetMilliseconds](./getmilliseconds/)(DateTime) const | Получает миллисекунды для указанного момента времени. |
| virtual [GetMinute](./getminute/)(DateTime) const | Получает минуты для указанного момента времени. |
| virtual [GetMonth](./getmonth/)(DateTime) const | Получает месяц для указанной временной точки. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Получает количество месяцев в указанном году. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Получает количество месяцев в указанном году. |
| virtual [GetSecond](./getsecond/)(DateTime) const | Получает секунды для указанного момента времени. |
| virtual [GetWeekOfYear](./getweekofyear/)(DateTime, CalendarWeekRule, DayOfWeek) const | Получает номер недели в году для указанного момента времени. |
| virtual [GetYear](./getyear/)(DateTime) const | Получает год для указанного момента времени. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Проверяет, является ли день високосным. |
| virtual [IsLeapDay](./isleapday/)(int, int, int, int) const | Проверяет, является ли день високосным. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Проверяет, является ли месяц високосным. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int, int) const | Проверяет, является ли месяц високосным. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Проверяет, является ли год високосным. |
| virtual [IsLeapYear](./isleapyear/)(int, int) const | Проверяет, является ли год високосным. |
| [IsValidDay](./isvalidday/)(int, int, int, int) const | Проверяет значения года, месяца, дня и эры. |
| [operator=](./operator=/)(const Calendar\&) |  |
| static [ReadOnly](./readonly/)(const CalendarPtr\&) | Получает только читаемую версию календаря. |
| virtual [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Устанавливает последний год, который может быть представлен двухзначным. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [ToFourDigitYear](./tofourdigityear/)(int) const | Преобразует год в четырёхзначный, используя свойство TwoDigitYearMax. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
