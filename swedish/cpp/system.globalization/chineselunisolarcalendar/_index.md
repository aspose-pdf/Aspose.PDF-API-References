---
title: "System::Globalization::ChineseLunisolarCalendar klass"
linktitle: "ChineseLunisolarCalendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::ChineseLunisolarCalendar klass. Kinesisk lunisolär kalender. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar class


Kinesisk lunisolär kalender. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | Standardkonstruktor. |
| [Clone](./clone/)() override | RTTI-information. |
| [get_Eras](./get_eras/)() const override | Hämtar lista över epoker som finns i kalendern. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Hämtar antal dagar i en specifik månad. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
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
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | Aktuell kinesisk era. |
## Se även

* Class [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
