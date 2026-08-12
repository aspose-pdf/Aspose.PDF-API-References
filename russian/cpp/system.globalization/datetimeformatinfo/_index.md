---
title: "Класс System::Globalization::DateTimeFormatInfo"
linktitle: "DateTimeFormatInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Globalization::DateTimeFormatInfo. Набор параметров форматирования даты и времени. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Набор параметров форматирования даты и времени. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонирует информацию о формате. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Конструктор по умолчанию, создаёт инвариантную информацию о формате. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Возвращает сокращённые названия дней. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Возвращает сокращённые названия месяцев в родительном падеже. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Возвращает сокращённые названия месяцев. |
| [get_AMDesignator](./get_amdesignator/)() const | Возвращает обозначение AM. |
| [get_Calendar](./get_calendar/)() const | Возвращает календарь, связанный с форматировщиком. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Возвращает правило недели календаря, связанное с форматировщиком. |
| static [get_CurrentInfo](./get_currentinfo/)() | Возвращает форматировщик даты и времени текущего потока. |
| [get_DateSeparator](./get_dateseparator/)() const | Возвращает разделитель даты. |
| [get_DayNames](./get_daynames/)() const | Возвращает названия дней. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Возвращает первый день недели. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Возвращает полный шаблон даты и времени. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Возвращает инвариантный форматировщик даты и времени. |
| [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли форматировщик только для чтения. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Возвращает длинный шаблон даты. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Получает шаблон длительного времени. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Получает шаблон дня месяца. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Получает названия месяцев в родительном падеже. |
| [get_MonthNames](./get_monthnames/)() const | Получает названия месяцев. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Получает название родного календаря, если доступно. |
| [get_PMDesignator](./get_pmdesignator/)() const | Получает обозначение PM. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Получает шаблон RFC1123. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Получает шаблон короткой даты. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Получает максимально короткие названия дней. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Получает шаблон короткого времени. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Получает шаблон сортируемой даты и времени. |
| [get_TimeSeparator](./get_timeseparator/)() const | Получает разделитель времени. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Получает универсальный сортируемый шаблон даты и времени. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Получает шаблон года и месяца. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Получает сокращённое название дня недели. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Получает сокращённое название эпохи. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Получает сокращённое название месяца. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Получает все шаблоны, в которых могут быть отформатированы значения даты и времени. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Получает все шаблоны, в которых могут быть отформатированы значения даты и времени с использованием указанной строки формата. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Получает название дня недели. |
| [GetEra](./getera/)(const String\&) const | Получает эпоху по названию. |
| [GetEraName](./geteraname/)(int) const | Получает название эпохи. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Получает форматировщик определённого типа. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Получает форматировщик, связанный с поставщиком формата. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Получает название високосного месяца. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Получает название месяца в родительном падеже. |
| [GetMonthName](./getmonthname/)(int) const | Получает название месяца. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Получает краткое название указанного дня недели. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Получает только для чтения версию форматировщика. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Устанавливает сокращённые названия дней. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | Устанавливает сокращённые названия месяцев в родительном падеже. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Устанавливает сокращённые названия месяцев. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | Устанавливает обозначение AM. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Устанавливает календарь, связанный с форматировщиком. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Устанавливает правило недели календаря, связанное с форматировщиком. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Устанавливает разделитель даты. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Устанавливает названия дней. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Устанавливает первый день недели. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Устанавливает полный шаблон даты и времени. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Устанавливает длинный шаблон даты. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Устанавливает длинный шаблон времени. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Устанавливает шаблон дня месяца. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Устанавливает названия месяцев в родительном падеже. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Устанавливает названия месяцев. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | Устанавливает обозначение PM. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Устанавливает короткий шаблон даты. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Устанавливает максимально короткие названия дней. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Устанавливает короткий шаблон времени. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Устанавливает разделитель времени. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Устанавливает шаблон года и месяца. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Устанавливает шаблоны для указанного формата. |
## См. также

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
