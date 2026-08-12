---
title: "System::Globalization::UmAlQuraCalendar klass"
linktitle: "UmAlQuraCalendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::UmAlQuraCalendar klass. Um Al Qura kalender. Ej implementerad. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Aldrig skapa en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Wrap alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3000
url: /sv/cpp/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar class


Um Al Qura-kalender. Ej implementerad. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | RTTI-information. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Hämtar algoritmtyp. |
| [get_Eras](./get_eras/)() const override | Hämtar lista över epoker som finns i kalendern. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Hämtar veckodag för den angivna tidpunkten. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skotmånad för det angivna året. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | RTTI-information. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är ett skottår. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Ställer in det sista året som kan representeras med två siffror. |
| [UmAlQuraCalendar](./umalquracalendar/)() | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | Aktuell UmAlQura-era. |
## Se även

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
