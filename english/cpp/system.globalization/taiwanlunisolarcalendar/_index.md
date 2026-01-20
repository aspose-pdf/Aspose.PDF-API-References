---
title: System::Globalization::TaiwanLunisolarCalendar class
linktitle: TaiwanLunisolarCalendar
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::TaiwanLunisolarCalendar class. Taiwan lunisolar calendar. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar class


Taiwan lunisolar calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | RTTI information. |
| [get_Eras](./get_eras/)() const override | Gets list of eras existing in calendar. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal point in time that is supported by the calendar. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal point in time that is supported by the calendar. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Gets number of days in specific month. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gets number of days in specific month. |
| [GetEra](./getera/)(DateTime) const override | Gets era for the specified time point. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Gets the leap month for the specified year. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Gets the leap month for the specified year. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Gets number of months in the specified year. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI information. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Checks if the day is leap. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Checks if the year is leap. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | Constructor. |
## See Also

* Class [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
