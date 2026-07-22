---
title: "System::TimeZoneInfo::TransitionTime::CreateTransitionTime metod"
linktitle: "CreateTransitionTime"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::TransitionTime::CreateTransitionTime metod. Skapar en instans av TransitionTime-klassen som representerar en tidsändring beskriven med de angivna parametrarna i C++."
type: docs
weight: 1200
url: /sv/cpp/system/timezoneinfo/transitiontime/createtransitiontime/
---
## TransitionTime::CreateTransitionTime method


Skapar en instans av [TransitionTime](../) klassen som representerar en tidsändring beskriven med de angivna parametrarna.

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateTransitionTime(DateTime time_of_day, int month, int week, int day, DayOfWeek day_of_week, bool is_fixed_date_rule)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| time_of_day | DateTime | Den specifika tidpunkten då tidsändringen sker. |
| månad | int | Den månad på året då tidsändringen sker. |
| vecka | int | Den vecka i månaden då tidsändringen sker. |
| dag | int | Dagen då tidsändringen sker. |
| day_of_week | DayOfWeek | Den veckodag då tidsändringen sker. |
| is_fixed_date_rule | bool | Värde som indikerar om tidsändringen sker på ett fast datum och tid eller ett flytande datum och tid. |

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
