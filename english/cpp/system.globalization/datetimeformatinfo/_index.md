---
title: System::Globalization::DateTimeFormatInfo class
linktitle: DateTimeFormatInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::DateTimeFormatInfo class. Set of date and time formatting parameters. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones format info. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Default constructor, constructs invariant format info. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Gets abbreviated day names. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Gets abbreviated month names in genitive form. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Gets abbreviated month names. |
| [get_AMDesignator](./get_amdesignator/)() const | Gets AM designator. |
| [get_Calendar](./get_calendar/)() const | Gets calendar associated with formatter. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Gets calendar week rule associated with formatter. |
| static [get_CurrentInfo](./get_currentinfo/)() | Gets current thread's date and time formatter. |
| [get_DateSeparator](./get_dateseparator/)() const | Gets date separator. |
| [get_DayNames](./get_daynames/)() const | Gets day names. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Gets first day of week. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Gets full date and time pattern. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Gets invariant date and time formatter. |
| [get_IsReadOnly](./get_isreadonly/)() const | Checks whether formatter is read-only. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Gets long date pattern. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Gets long time pattern. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Gets month day pattern. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Gets month names in genitive form. |
| [get_MonthNames](./get_monthnames/)() const | Gets month names. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Gets native calendar name if available. |
| [get_PMDesignator](./get_pmdesignator/)() const | Gets PM designator. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Gets RFC1123 pattern. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Gets short date pattern. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Gets shortest day names possible. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Gets short time pattern. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Gets sortable date and time pattern. |
| [get_TimeSeparator](./get_timeseparator/)() const | Gets time separator. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Gets universal sortable date and time pattern. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Gets year and month pattern. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Gets abbreviated week day name. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Gets abbreviated era name. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Gets abbreviated month name. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Gets all patterns in which date and time values can be formatted. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Gets all patterns in which date and time values can be formatted using specified format string. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Gets week day name. |
| [GetEra](./getera/)(const String\&) const | Gets era by name. |
| [GetEraName](./geteraname/)(int) const | Gets era name. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Gets formatter of specific type. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Gets formatter associated with format provider. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Gets leap-year month name. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Gets genitive month name. |
| [GetMonthName](./getmonthname/)(int) const | Gets month name. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Gets shortes name for the specified day of week. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Gets read-only version of formatter. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Sets abbreviated day names. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | Sets abbreviated month names in genitive form. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Sets abbreviated month names. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | Sets AM designator. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Sets calendar associated with formatter. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Sets calendar week rule associated with formatter. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Sets date separator. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Sets day names. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Sets first day of week. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Sets full date and time pattern. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Sets long date pattern. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Sets long time pattern. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Sets month day pattern. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Sets month names in genitive form. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Sets month names. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | Sets PM designator. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Sets short date pattern. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Sets shortest day names possible. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Sets short time pattern. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Sets time separator. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Sets year and month pattern. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Sets patterns for the specified format. |
## See Also

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
