---
title: "System::Globalization::KoreanCalendar klass"
linktitle: "KoreanCalendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::KoreanCalendar klass. Koreansk kalender. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1700
url: /sv/cpp/system.globalization/koreancalendar/
---
## KoreanCalendar class


Koreansk kalender. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | RTTI-information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Hämtar algoritmtyp. |
| [get_Eras](./get_eras/)() const override | Hämtar lista över epoker som finns i kalendern. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| [GetDayOfMonth](./getdayofmonth/)(DateTime) const override | Hämtar dag i månaden för den angivna tidpunkten. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Hämtar veckodag för den angivna tidpunkten. |
| [GetDayOfYear](./getdayofyear/)(DateTime) const override | Hämtar dag på året för den angivna tidpunkten. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Hämtar antal dagar i en specifik månad. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Hämtar antal dagar i ett specifikt år. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Hämtar antal dagar i ett specifikt år. |
| [GetEra](./getera/)(DateTime) const override | Hämtar epok för den angivna tidpunkten. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skotmånad för det angivna året. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Hämtar skotmånad för det angivna året. |
| [GetMonth](./getmonth/)(DateTime) const override | Hämtar månad för den angivna tidpunkten. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Hämtar antal månader i det angivna året. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-information. |
| [GetYear](./getyear/)(DateTime) const override | Hämtar år för den angivna tidpunkten. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är ett skottår. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| [KoreanCalendar](./koreancalendar/)() | Konstruktor. |
| [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Skapar [DateTime](../../system/datetime/) objekt från komponenter. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Skapar [DateTime](../../system/datetime/) objekt från komponenter. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | Aktuell koreansk era. |
## Se även

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
