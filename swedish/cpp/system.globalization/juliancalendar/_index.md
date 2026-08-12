---
title: "System::Globalization::JulianCalendar klass"
linktitle: "JulianCalendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::JulianCalendar klass. Juliansk kalender. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1600
url: /sv/cpp/system.globalization/juliancalendar/
---
## JulianCalendar class


Juliansk kalender. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med [System::SmartPtr](../../system/smartptr/)-pekaren och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class JulianCalendar : public System::Globalization::Calendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | RTTI-information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Hämtar algoritmtyp. |
| [get_Eras](./get_eras/)() const override | Hämtar lista över epoker som finns i kalendern. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Hämtar antal dagar i en specifik månad. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Hämtar antal dagar i ett specifikt år. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Hämtar antal dagar i ett specifikt år. |
| [GetEra](./getera/)(DateTime) const override | Hämtar epok för den angivna tidpunkten. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skotmånad för det angivna året. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Hämtar skotmånad för det angivna året. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Hämtar antal månader i det angivna året. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-information. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är ett skottår. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| [JulianCalendar](./juliancalendar/)() | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [JulianEra](./julianera/) | Aktuell julianska era. |
## Se även

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
