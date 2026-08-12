---
title: "System::TimeZoneInfo::TransitionTime klass"
linktitle: "TransitionTime"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::TransitionTime klass. RTTI-information i C++."
type: docs
weight: 3400
url: /sv/cpp/system/timezoneinfo/transitiontime/
---
## TransitionTime class


RTTI-information.

```cpp
class TransitionTime
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateFixedDateRule](./createfixeddaterule/)(DateTime, int, int) | Skapar en instans av [TransitionTime](./) klass som representerar en fast datum-regel (tidsändring som sker på en specifik dag i en specifik månad). |
| static [CreateFloatingDateRule](./createfloatingdaterule/)(DateTime, int, int, DayOfWeek) | Skapar en instans av [TransitionTime](./) klass som representerar en flytande datum-regel (tidsändring som sker på en specifik dag i en specifik vecka i en specifik månad). |
| static [CreateTransitionTime](./createtransitiontime/)(DateTime, int, int, int, DayOfWeek, bool) | Skapar en instans av [TransitionTime](./) klass som representerar en tidsändring beskriven med de angivna parametrarna. |
| [get_Day](./get_day/)() const | Returnerar ordningsnumret för veckodagen då tidsändringen sker. |
| [get_DayOfWeek](./get_dayofweek/)() const | Returnerar värdet som representerar veckodagen då tidsändringen sker. |
| [get_IsFixedDateRule](./get_isfixeddaterule/)() const | Returnerar värdet som indikerar om tidsändringen sker på ett fast datum och tid eller ett flytande datum och tid. |
| [get_Month](./get_month/)() const | Returnerar ordningsnumret för månaden på året då tidsändringen sker. |
| [get_TimeOfDay](./get_timeofday/)() const | Returnerar ett [DateTime](../../datetime/)‑objekt som representerar den specifika tidpunkten då tidsändringen sker. |
| [get_Week](./get_week/)() const | Returnerar ordningsnumret för veckan i månaden då tidsändringen sker. |
| [operator!=](./operator!=/)(const TransitionTime\&) const |  |
| [operator==](./operator==/)(const TransitionTime\&) const |  |
| [TransitionTime](./transitiontime/)() | Standardkonstruktor. FÖR INTERNT ANVÄNDNING. |
## Anmärkningar


Tillhandahåller information om en tidsändring i en tidszon.
## Se även

* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
