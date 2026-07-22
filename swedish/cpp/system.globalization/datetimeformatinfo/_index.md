---
title: "System::Globalization::DateTimeFormatInfo klass"
linktitle: "DateTimeFormatInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::DateTimeFormatInfo klass. Uppsättning av datum- och tidsformateringsparametrar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Uppsättning av datum- och tidsformateringsparametrar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar formatinformation. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Standardkonstruktor, skapar invariant formatinformation. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Hämtar förkortade dagnamn. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Hämtar förkortade månadsnamn i genitivform. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Hämtar förkortade månadsnamn. |
| [get_AMDesignator](./get_amdesignator/)() const | Hämtar AM-designator. |
| [get_Calendar](./get_calendar/)() const | Hämtar kalender associerad med formateraren. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Hämtar kalendervecko-regel associerad med formateraren. |
| static [get_CurrentInfo](./get_currentinfo/)() | Hämtar den aktuella trådens datum- och tidsformaterare. |
| [get_DateSeparator](./get_dateseparator/)() const | Hämtar datumseparator. |
| [get_DayNames](./get_daynames/)() const | Hämtar dagnamn. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Hämtar veckans första dag. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Hämtar fullständigt datum- och tidsmönster. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Hämtar invariant datum- och tidsformaterare. |
| [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om formateraren är skrivskyddad. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Hämtar långt datumformat. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Hämtar långt tidsformat. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Hämtar månad‑dag‑mönster. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Hämtar månadsnamn i genitivform. |
| [get_MonthNames](./get_monthnames/)() const | Hämtar månadsnamn. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Hämtar det inhemska kalendrarens namn om tillgängligt. |
| [get_PMDesignator](./get_pmdesignator/)() const | Hämtar PM‑indikator. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Hämtar RFC1123‑mönster. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Hämtar kort datumformat. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Hämtar kortaste möjliga veckodagsnamn. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Hämtar kort tidsformat. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Hämtar sorteringsbart datum‑ och tidsformat. |
| [get_TimeSeparator](./get_timeseparator/)() const | Hämtar tidsseparator. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Hämtar universellt sorteringsbart datum‑ och tidsformat. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Hämtar år‑ och månadsformat. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Hämtar förkortat veckodagsnamn. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Hämtar förkortat eranamn. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Hämtar förkortat månadsnamn. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Hämtar alla mönster som datum‑ och tidsvärden kan formateras i. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Hämtar alla mönster som datum‑ och tidsvärden kan formateras i med angiven formatsträng. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Hämtar veckodagsnamn. |
| [GetEra](./getera/)(const String\&) const | Hämtar era efter namn. |
| [GetEraName](./geteraname/)(int) const | Hämtar eranamn. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Hämtar formaterare av specifik typ. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Hämtar formaterare som är associerad med formatleverantör. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Hämtar skottårs‑månadsnamn. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Hämtar månadsnamn i genitiv. |
| [GetMonthName](./getmonthname/)(int) const | Hämtar månadsnamn. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Hämtar kortaste namnet för den angivna veckodagen. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Hämtar skrivskyddad version av formaterare. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Ställer in förkortade veckodagsnamn. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | Ställer in förkortade månadsnamn i genitivform. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Ställer in förkortade månadsnamn. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | Ställer in AM-beteckning. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Ställer in kalender som är associerad med formateraren. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Ställer in kalenderveckoregeln som är associerad med formateraren. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Ställer in datumseparator. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Ställer in veckodagsnamn. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Ställer in första veckodag. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Ställer in fullständigt datum- och tidsformat. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Ställer in långt datumformat. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Ställer in långt tidsformat. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Ställer in mönster för månad och dag. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Ställer in månadsnamn i genitivform. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Ställer in månadsnamn. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | Ställer in PM-beteckning. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Ställer in kort datumformat. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Ställer in kortaste möjliga veckodagsnamn. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Ställer in kort tidsformat. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Ställer in tidsseparator. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Ställer in år- och månadsformat. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Ställer in mönster för det angivna formatet. |
## Se även

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
