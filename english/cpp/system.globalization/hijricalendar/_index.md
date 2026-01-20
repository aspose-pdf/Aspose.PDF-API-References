---
title: System::Globalization::HijriCalendar class
linktitle: HijriCalendar
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::HijriCalendar class. Hijri calendar. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.globalization/hijricalendar/
---
## HijriCalendar class


Hijri calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | RTTI information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Gets algorithm type. |
| [get_Eras](./get_eras/)() const override | Gets list of eras existing in calendar. |
| [get_HijriAdjustment](./get_hijriadjustment/)() const | Gets hijri adjustment. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal point in time that is supported by the calendar. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal point in time that is supported by the calendar. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Gets day of week for the specified time point. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Gets the leap month for the specified year. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | RTTI information. |
| [HijriCalendar](./hijricalendar/)() | Constructor. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Checks if the day is leap. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Checks if the month is leap. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Checks if the month is leap. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Checks if the year is leap. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| [set_HijriAdjustment](./set_hijriadjustment/)(int) | Sets hijri adjustment. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | Current hijri era. |
## See Also

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
