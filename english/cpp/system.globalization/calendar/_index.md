---
title: System::Globalization::Calendar class
linktitle: Calendar
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::Calendar class. Calendar which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.globalization/calendar/
---
## Calendar class


[Calendar](./) which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Calendar : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddDays](./adddays/)(DateTime, int) const | Adds days to time point. |
| virtual [AddHours](./addhours/)(DateTime, int) const | Adds hours to time point. |
| virtual [AddMilliseconds](./addmilliseconds/)(DateTime, double) const | Adds milliseconds to time point. |
| virtual [AddMinutes](./addminutes/)(DateTime, int) const | Adds minutes to time point. |
| virtual [AddMonths](./addmonths/)(DateTime, int) const | Adds months to time point. |
| virtual [AddSeconds](./addseconds/)(DateTime, int) const | Adds seconds to time point. |
| virtual [AddWeeks](./addweeks/)(DateTime, int) const | Adds weeks to time point. |
| virtual [AddYears](./addyears/)(DateTime, int) const | Adds years to time point. |
| [Calendar](./calendar/)(const Calendar\&) | RTTI information. |
| virtual [get_AlgorithmType](./get_algorithmtype/)() const | Gets algorithm type. |
| [get_CurrentEra](./get_currentera/)() const | Gets index of current era. |
| [get_CurrentEraValue](./get_currenteravalue/)() const | Gets value of current era. |
| virtual [get_Eras](./get_eras/)() const | Gets list of eras existing in calendar. |
| virtual [get_ID](./get_id/)() const | Gets calendar identifier. |
| [get_IsReadOnly](./get_isreadonly/)() const | Checks if the calendar is read only. |
| virtual [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Maximal point in time that is supported by the calendar. |
| virtual [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Minimal point in time that is supported by the calendar. |
| virtual [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Gets the last year that can be represented by a 2-digit. |
| virtual [GetDayOfMonth](./getdayofmonth/)(DateTime) const | Gets day of month for the specified time point. |
| virtual [GetDayOfWeek](./getdayofweek/)(DateTime) const | Gets day of week for the specified time point. |
| virtual [GetDayOfYear](./getdayofyear/)(DateTime) const | Gets day of year for the specified time point. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gets number of days in specific month. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Gets number of days in specific month. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Gets number of days in specific year. |
| virtual [GetDaysInYear](./getdaysinyear/)(int, int) const | Gets number of days in specific year. |
| virtual [GetEra](./getera/)(DateTime) const | Gets era for the specified time point. |
| virtual [GetHour](./gethour/)(DateTime) const | Gets hours for the specified time point. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Gets the leap month for the specified year. |
| virtual [GetLeapMonth](./getleapmonth/)(int, int) const | Gets the leap month for the specified year. |
| virtual [GetMilliseconds](./getmilliseconds/)(DateTime) const | Gets milliseconds for the specified time point. |
| virtual [GetMinute](./getminute/)(DateTime) const | Gets minutes for the specified time point. |
| virtual [GetMonth](./getmonth/)(DateTime) const | Gets month for the specified time point. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Gets number of months in the specified year. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Gets number of months in the specified year. |
| virtual [GetSecond](./getsecond/)(DateTime) const | Gets seconds for the specified time point. |
| virtual [GetWeekOfYear](./getweekofyear/)(DateTime, CalendarWeekRule, DayOfWeek) const | Gets week of the year for the specified time point. |
| virtual [GetYear](./getyear/)(DateTime) const | Gets year for the specified time point. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| virtual [IsLeapDay](./isleapday/)(int, int, int, int) const | Checks if the day is leap. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Checks if the month is leap. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int, int) const | Checks if the month is leap. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| virtual [IsLeapYear](./isleapyear/)(int, int) const | Checks if the year is leap. |
| [IsValidDay](./isvalidday/)(int, int, int, int) const | Checks year, month, day and era values. |
| [operator=](./operator=/)(const Calendar\&) |  |
| static [ReadOnly](./readonly/)(const CalendarPtr\&) | Gets read only version of calendar. |
| virtual [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Sets the last year that can be represented by a 2-digit. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Constructs [DateTime](../../system/datetime/) object from components. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Constructs [DateTime](../../system/datetime/) object from components. |
| virtual [ToFourDigitYear](./tofourdigityear/)(int) const | Converts the year to 4-digit year using TwoDigitYearMax property. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
