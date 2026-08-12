---
title: "System::Globalization::Calendar klass"
linktitle: "Calendar"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::Calendar klass. Kalender som definierar hur datum hanteras, beräknas, formateras osv. Sättningsoperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.globalization/calendar/
---
## Calendar class


[Calendar](./) which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Calendar : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AddDays](./adddays/)(DateTime, int) const | Lägger till dagar till tidpunkten. |
| virtual [AddHours](./addhours/)(DateTime, int) const | Lägger till timmar till tidpunkten. |
| virtual [AddMilliseconds](./addmilliseconds/)(DateTime, double) const | Lägger till millisekunder till tidpunkten. |
| virtual [AddMinutes](./addminutes/)(DateTime, int) const | Lägger till minuter till tidpunkten. |
| virtual [AddMonths](./addmonths/)(DateTime, int) const | Lägger till månader till tidpunkten. |
| virtual [AddSeconds](./addseconds/)(DateTime, int) const | Lägger till sekunder till tidpunkten. |
| virtual [AddWeeks](./addweeks/)(DateTime, int) const | Lägger till veckor till tidpunkten. |
| virtual [AddYears](./addyears/)(DateTime, int) const | Lägger till år till tidpunkten. |
| [Calendar](./calendar/)(const Calendar\&) | RTTI-information. |
| virtual [get_AlgorithmType](./get_algorithmtype/)() const | Hämtar algoritmtyp. |
| [get_CurrentEra](./get_currentera/)() const | Hämtar index för den aktuella epoken. |
| [get_CurrentEraValue](./get_currenteravalue/)() const | Hämtar värdet för den aktuella epoken. |
| virtual [get_Eras](./get_eras/)() const | Hämtar lista över epoker som finns i kalendern. |
| virtual [get_ID](./get_id/)() const | Hämtar kalenderidentifierare. |
| [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om kalendern är skrivskyddad. |
| virtual [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Maximal tidpunkt som stöds av kalendern. |
| virtual [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Minimal tidpunkt som stöds av kalendern. |
| virtual [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Hämtar det sista året som kan representeras med två siffror. |
| virtual [GetDayOfMonth](./getdayofmonth/)(DateTime) const | Hämtar dag i månaden för den angivna tidpunkten. |
| virtual [GetDayOfWeek](./getdayofweek/)(DateTime) const | Hämtar veckodag för den angivna tidpunkten. |
| virtual [GetDayOfYear](./getdayofyear/)(DateTime) const | Hämtar dag på året för den angivna tidpunkten. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Hämtar antal dagar i ett specifikt år. |
| virtual [GetDaysInYear](./getdaysinyear/)(int, int) const | Hämtar antal dagar i ett specifikt år. |
| virtual [GetEra](./getera/)(DateTime) const | Hämtar epok för den angivna tidpunkten. |
| virtual [GetHour](./gethour/)(DateTime) const | Hämtar timmar för den angivna tidpunkten. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Hämtar skotmånad för det angivna året. |
| virtual [GetLeapMonth](./getleapmonth/)(int, int) const | Hämtar skotmånad för det angivna året. |
| virtual [GetMilliseconds](./getmilliseconds/)(DateTime) const | Hämtar millisekunder för den angivna tidpunkten. |
| virtual [GetMinute](./getminute/)(DateTime) const | Hämtar minuter för den angivna tidpunkten. |
| virtual [GetMonth](./getmonth/)(DateTime) const | Hämtar månad för den angivna tidpunkten. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Hämtar antal månader i det angivna året. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Hämtar antal månader i det angivna året. |
| virtual [GetSecond](./getsecond/)(DateTime) const | Hämtar sekunder för den angivna tidpunkten. |
| virtual [GetWeekOfYear](./getweekofyear/)(DateTime, CalendarWeekRule, DayOfWeek) const | Hämtar veckonummer för året för den angivna tidpunkten. |
| virtual [GetYear](./getyear/)(DateTime) const | Hämtar år för den angivna tidpunkten. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapDay](./isleapday/)(int, int, int, int) const | Kontrollerar om dagen är en skottdag. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int, int) const | Kontrollerar om månaden är en skottmånad. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| virtual [IsLeapYear](./isleapyear/)(int, int) const | Kontrollerar om året är ett skottår. |
| [IsValidDay](./isvalidday/)(int, int, int, int) const | Kontrollerar år, månad, dag och epokvärden. |
| [operator=](./operator=/)(const Calendar\&) |  |
| static [ReadOnly](./readonly/)(const CalendarPtr\&) | Hämtar en skrivskyddad version av kalendern. |
| virtual [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Ställer in det sista året som kan representeras med två siffror. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Skapar [DateTime](../../system/datetime/) objekt från komponenter. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Skapar [DateTime](../../system/datetime/) objekt från komponenter. |
| virtual [ToFourDigitYear](./tofourdigityear/)(int) const | Konverterar året till ett fyrsiffrigt år med hjälp av egenskapen TwoDigitYearMax. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
