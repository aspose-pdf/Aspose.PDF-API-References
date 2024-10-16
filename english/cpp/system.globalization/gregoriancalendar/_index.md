---
title: System::Globalization::GregorianCalendar class
linktitle: GregorianCalendar
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::GregorianCalendar class. Gregorian calendar. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.globalization/gregoriancalendar/
---
## GregorianCalendar class


Gregorian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | RTTI information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Gets algorithm type. |
| virtual [get_CalendarType](./get_calendartype/)() const | Gets Gregorian calendar type. |
| [get_Eras](./get_eras/)() const override | Gets list of eras existing in calendar. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal point in time that is supported by the calendar. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal point in time that is supported by the calendar. |
| [GetDayOfMonth](./getdayofmonth/)(DateTime) const override | Gets day of month for the specified time point. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Gets day of week for the specified time point. |
| [GetDayOfYear](./getdayofyear/)(DateTime) const override | Gets day of year for the specified time point. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Gets number of days in specific month. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gets number of days in specific month. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Gets number of days in specific year. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Gets number of days in specific year. |
| static [GetDefaultInstance](./getdefaultinstance/)() | Gets default gregorian calendar instance. |
| [GetEra](./getera/)(DateTime) const override | Gets era for the specified time point. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Gets the leap month for the specified year. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Gets the leap month for the specified year. |
| [GetMonth](./getmonth/)(DateTime) const override | Gets month for the specified time point. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Gets number of months in the specified year. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI information. |
| [GetYear](./getyear/)(DateTime) const override | Gets year for the specified time point. |
| [GregorianCalendar](./gregoriancalendar/)(GregorianCalendarTypes) | Constructs specific gregorian calendar. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Checks if the day is leap. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Checks if the month is leap. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Checks if the month is leap. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Checks if the year is leap. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| virtual [set_CalendarType](./set_calendartype/)(GregorianCalendarTypes) | Sets Gregorian calendar type. |
| [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Constructs [DateTime](../../system/datetime/) object from components. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Constructs [DateTime](../../system/datetime/) object from components. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [ADEra](./adera/) | Current era. |
## See Also

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
