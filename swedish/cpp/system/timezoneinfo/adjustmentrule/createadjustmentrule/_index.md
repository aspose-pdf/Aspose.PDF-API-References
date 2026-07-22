---
title: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule metod"
linktitle: "CreateAdjustmentRule"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule metod. Skapar en instans av klassen AdjustmentRule som representerar en tidsjusteringsregel beskriven med de angivna parametrarna i C++."
type: docs
weight: 1000
url: /sv/cpp/system/timezoneinfo/adjustmentrule/createadjustmentrule/
---
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) method


Skapar en instans av klassen [AdjustmentRule](../) som representerar en tidsjusteringsregel beskriven med de angivna parametrarna.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_start | DateTime | Datumet och tiden då justeringsregeln träder i kraft. |
| date_end | DateTime | Datumet och tiden då justeringsregeln slutar att gälla. |
| daylight_delta | TimeSpan | Den tid som krävs för att skapa sommartiden för tidszonen. |
| daylight_transition_start | const TransitionTime\& | Informationen om övergången från sommartid till standardtid. |
| daylight_transition_end | const TransitionTime\& | Informationen om övergången från standardtid till sommartid. |

### ReturnValue

En instans av klassen [AdjustmentRule](../) som representerar den beskrivna tidszonsjusteringsregeln.

## Se även

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) method


Skapar en instans av klassen [AdjustmentRule](../) som representerar en tidsjusteringsregel beskriven med de angivna parametrarna.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end, TimeSpan base_utc_offset_delta, bool no_daylight_transitions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_start | DateTime | Datumet och tiden då justeringsregeln träder i kraft. |
| date_end | DateTime | Datumet och tiden då justeringsregeln slutar att gälla. |
| daylight_delta | TimeSpan | Den tid som krävs för att skapa sommartiden för tidszonen. |
| daylight_transition_start | const TransitionTime\& | Informationen om övergången från sommartid till standardtid. |
| daylight_transition_end | const TransitionTime\& | Informationen om övergången från standardtid till sommartid. |
| base_utc_offset_delta | TimeSpan | Delta från standard-UTC-förskjutningen. |
| no_daylight_transitions | bool | Anger om justeringsregeln förutsätter övergången till sommartid. |

### ReturnValue

En instans av klassen [AdjustmentRule](../) som representerar den beskrivna tidszonsjusteringsregeln.

## Se även

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
