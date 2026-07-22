---
title: "System::Globalization::HijriCalendar klass"
linktitle: "HijriCalendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::HijriCalendar klass. Hijri‑kalender. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.globalization/hijricalendar/
---
## HijriCalendar class


Hijri‑kalender. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | RTTI-information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Hämtar algoritmtyp. |
| [get_Eras](./get_eras/)() const override | Hämtar lista över epoker som finns i kalendern. |
| [get_HijriAdjustment](./get_hijriadjustment/)() const | Hämtar hijri‑justering. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Hämtar veckodag för den angivna tidpunkten. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skotmånad för det angivna året. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | RTTI-information. |
| [HijriCalendar](./hijricalendar/)() | Konstruktor. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är ett skottår. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| [set_HijriAdjustment](./set_hijriadjustment/)(int) | Ställer in hijri‑justering. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | Aktuell hijri‑era. |
## Se även

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
