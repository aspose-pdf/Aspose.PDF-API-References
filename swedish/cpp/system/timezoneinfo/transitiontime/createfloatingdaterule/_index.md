---
title: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule metod"
linktitle: "CreateFloatingDateRule"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule metod. Skapar en instans av klassen TransitionTime som representerar en flytande datumregel (tidsändring som sker på en specifik dag i en specifik vecka i en specifik månad) i C++."
type: docs
weight: 1100
url: /sv/cpp/system/timezoneinfo/transitiontime/createfloatingdaterule/
---
## TransitionTime::CreateFloatingDateRule method


Skapar en instans av klassen [TransitionTime](../) som representerar en flytande datumregel (tidsändring som sker på en specifik dag i en specifik vecka i en specifik månad).

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule(DateTime time_of_day, int month, int week, DayOfWeek day_of_week)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| time_of_day | DateTime | Den specifika tidpunkten då tidsändringen sker. |
| månad | int | Den månad på året då tidsändringen sker. |
| vecka | int | Den vecka i månaden då tidsändringen sker. |
| day_of_week | DayOfWeek | Den veckodag då tidsändringen sker. |

### ReturnValue

En instans av klassen [TransitionTime](../) som representerar den beskrivna tidsändringen.

## Se även

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
