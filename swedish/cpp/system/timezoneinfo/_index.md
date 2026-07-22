---
title: "System::TimeZoneInfo-klass"
linktitle: "TimeZoneInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo-klass. Representerar information som beskriver en specifik tidszon. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 6600
url: /sv/cpp/system/timezoneinfo/
---
## TimeZoneInfo class


Representerar information som beskriver en specifik tidszon. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Nested classes

* Class [AdjustmentRule](./adjustmentrule/)
* Class [TransitionTime](./transitiontime/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ClearCachedData](./clearcacheddata/)() | Rensa cachad tidszondata. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) tid från en tidszon till en annan. |
| static [ConvertTime](./converttime/)(const DateTimeOffset\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) tid till tiden i en specificerad tidszon. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&) | [Convert](../convert/) tid till tiden i en specificerad tidszon. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&) | [Convert](../convert/) tid till tiden i en specificerad tidszon. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const DateTimeOffset\&, const String\&) | [Convert](../convert/) tid till tiden i en specificerad tidszon. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&, const String\&) | [Convert](../convert/) tid till tiden i en specificerad tidszon. |
| static [ConvertTimeFromUtc](./converttimefromutc/)(DateTime, const TimeZoneInfoPtr\&) | Konverterar UTC-tid till tiden i en specificerad tidszon. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime, const TimeZoneInfoPtr\&) | Konverterar tid till UTC-tid. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime) | Konverterar tid till UTC-tid. |
| static [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)(DateTime) | Konverterar tid till UTC-tid. FÖR INTERNT BRUK. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) | Skapar en anpassad tidszon. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) | Skapar en anpassad tidszon. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&) | Skapar en anpassad tidszon. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(TimeZoneInfoPtr) override | Bestämmer om de aktuella och angivna objekten är lika. |
| static [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const String\&) | Hämtar tidszon med specificerad identifierare. |
| [get_BaseUtcOffset](./get_baseutcoffset/)() const | Returnerar en instans av [TimeSpan](../timespan/) som representerar ett tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| [get_DaylightName](./get_daylightname/)() const | Hämtar namn för den aktuella tidszonens sommartid. |
| [get_DisplayName](./get_displayname/)() const | Hämtar namn för den aktuella tidszonen. |
| [get_Id](./get_id/)() const | Returnerar identifieraren för tidszonen som representeras av det aktuella objektet. |
| static [get_Local](./get_local/)() | Returnerar en instans av [TimeZoneInfo](./) som representerar en lokal tidszon. |
| [get_StandardName](./get_standardname/)() const | Hämtar namn för den aktuella tidszonens standardtid. |
| [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Hämtar flagga som indikerar om tidszonen har sommartidsregler. |
| static [get_Utc](./get_utc/)() | Returnerar en instans av [TimeZoneInfo](./) som representerar en UTC-tidszon. |
| [GetAdjustmentRules](./getadjustmentrules/)() const | Returnerar en array bestående av [AdjustmentRule](./adjustmentrule/)‑objekt som representerar justeringsregler som gäller för det aktuella [TimeZoneInfo](./)-objektet. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(DateTime) const | Hämtar UTC‑datum och -tider som ett specificerat datum och tid kan avbildas till. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const DateTimeOffset\&) const | Hämtar UTC‑datum och -tider som ett specificerat datum och tid kan avbildas till. |
| [GetHashCode](./gethashcode/)() const override | Analog till C#‑metoden [Object.GetHashCode()](../object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| static [GetSystemTimeZones](./getsystemtimezones/)() | Hämtar en sorterad samling av alla tidszoner som finns tillgängliga på det lokala systemet. |
| [GetUtcOffset](./getutcoffset/)(DateTime) const | Beräknar skillnaden mellan tiden i denna tidszon och UTC‑tidszonen för ett specificerat datum och tid. |
| [GetUtcOffset](./getutcoffset/)(const DateTimeOffset\&) const | Beräknar skillnaden mellan tiden i denna tidszon och UTC‑tidszonen för ett specificerat datum och tid. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&) | Intern hjälpfunktion som returnerar UTC‑offseten för ett UTC‑datum/tid i en specificerad tidszon. FÖR INTERNT ANVÄNDANDE. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&, bool\&, bool\&) | Intern hjälpfunktion som returnerar UTC‑offseten för ett UTC‑datum/tid i en specificerad tidszon. FÖR INTERNT ANVÄNDANDE. |
| [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)(DateTime) const | Beräknar skillnaden mellan tiden i denna tidszon och UTC‑tidszonen för ett specificerat datum och tid. FÖR INTERNT ANVÄNDANDE. |
| [HasSameRules](./hassamerules/)(const TimeZoneInfoPtr\&) const | Kontrollerar om den aktuella och en annan tidszon har samma justeringsregler. |
| [IsAmbiguousTime](./isambiguoustime/)(DateTime) const | Kontrollerar om det specificerade datumet och tiden är tvetydig och kan avbildas till flera UTC‑tider. |
| [IsAmbiguousTime](./isambiguoustime/)(const DateTimeOffset\&) const | Kontrollerar om det specificerade datumet och tiden är tvetydig och kan avbildas till flera UTC‑tider. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) const | Kontrollerar om det specificerade datumet och tiden faller inom sommartidsintervallet. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(const DateTimeOffset\&) const | Kontrollerar om det specificerade datumet och tiden faller inom sommartidsintervallet. |
| [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)(DateTime) const | Kontrollerar om det specificerade datumet och tiden faller inom sommartidsintervallet. |
| [IsInvalidTime](./isinvalidtime/)(DateTime) const | Kontrollerar om det specificerade datumet och tiden är ogiltig. |
| [ToString](./tostring/)() const override | Analog till C#‑metoden [Object.ToString()](../object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static [TransitionTimeToDateTime](./transitiontimetodatetime/)(int32_t, const TransitionTime\&) | Hjälpfunktion som konverterar ett år och [TransitionTime](./transitiontime/) till ett [DateTime](../datetime/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | Ett alias för en delad pekare till en instans av klassen [AdjustmentRule](./adjustmentrule/). |
## Se även

* Class [IEquatable](../iequatable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
