---
title: System::Globalization::PersianCalendar class
linktitle: PersianCalendar
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::PersianCalendar class. Persian calendar. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.globalization/persiancalendar/
---
## PersianCalendar class


Persian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PersianCalendar : public System::Globalization::Calendar
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | RTTI information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Gets algorithm type. |
| [get_Eras](./get_eras/)() const override | Gets list of eras existing in calendar. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal point in time that is supported by the calendar. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal point in time that is supported by the calendar. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Gets day of week for the specified time point. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Gets number of days in specific month. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | RTTI information. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Gets number of days in specific year. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Gets number of days in specific year. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Gets the leap month for the specified year. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Gets the leap month for the specified year. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Gets number of months in the specified year. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Gets number of months in the specified year. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Checks if the day is leap. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Checks if the month is leap. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Checks if the month is leap. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Checks if the year is leap. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| [PersianCalendar](./persiancalendar/)() | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | Current persian era. |
## See Also

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
