---
title: "System::TimeZoneInfo::AdjustmentRule‑klass"
linktitle: "AdjustmentRule"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::AdjustmentRule‑klass. Tillhandahåller information om en tidszonsjustering. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3300
url: /sv/cpp/system/timezoneinfo/adjustmentrule/
---
## AdjustmentRule class


Tillhandahåller information om en tidszonsjustering. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AdjustmentRule : public System::IEquatable<AdjustmentRulePtr>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) | Skapar en instans av [AdjustmentRule](./)-klassen som representerar en tidsjusteringsregel beskriven med de angivna parametrarna. |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) | Skapar en instans av [AdjustmentRule](./)-klassen som representerar en tidsjusteringsregel beskriven med de angivna parametrarna. |
| [Equals](./equals/)(AdjustmentRulePtr) override |  |
| [get_BaseUtcOffsetDelta](./get_baseutcoffsetdelta/)() const | Returnerar en delta från standard‑UTC‑offseten. |
| [get_DateEnd](./get_dateend/)() const | Returnerar ett [DateTime](../../datetime/)-objekt som representerar datum och tid då justeringsregeln slutar vara giltig. |
| [get_DateStart](./get_datestart/)() const | Returnerar ett [DateTime](../../datetime/)-objekt som representerar datum och tid då justeringsregeln träder i kraft. |
| [get_DaylightDelta](./get_daylightdelta/)() const | Returnerar ett [TimeSpan](../../timespan/)-objekt som representerar den tid som krävs för att bilda sommartid för tidszonen. |
| [get_DaylightTransitionEnd](./get_daylighttransitionend/)() const | Returnerar information om övergången från standardtid till sommartid. |
| [get_DaylightTransitionStart](./get_daylighttransitionstart/)() const | Returnerar information om övergången från sommartid till standardtid. |
| [get_HasDaylightSaving](./get_hasdaylightsaving/)() const | FÖR INTERNT ANVÄNDNING. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
## Se även

* Class [IEquatable](../../iequatable/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
