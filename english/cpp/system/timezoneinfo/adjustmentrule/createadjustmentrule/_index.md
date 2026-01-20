---
title: System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule method
linktitle: CreateAdjustmentRule
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule method. Constructs an instance of AdjustmentRule class that represents a time adjustment rule described with the specified parameters in C++.'
type: docs
weight: 1000
url: /cpp/system/timezoneinfo/adjustmentrule/createadjustmentrule/
---
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) method


Constructs an instance of [AdjustmentRule](../) class that represents a time adjustment rule described with the specified parameters.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| date_start | DateTime | The date and time when the adjustment rule comes into effect. |
| date_end | DateTime | The date and time when the adjustment rule stops being effectvie. |
| daylight_delta | TimeSpan | The amount of time required to form the daylight saving time of the time zone. |
| daylight_transition_start | const TransitionTime\& | The information about transition from daylight saving time to standard time. |
| daylight_transition_end | const TransitionTime\& | The information about transition from standard time to daylight saving time. |

### ReturnValue

An instance of [AdjustmentRule](../) class that represents the described time zone adjustment rule.

## See Also

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) method


Constructs an instance of [AdjustmentRule](../) class that represents a time adjustment rule described with the specified parameters.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end, TimeSpan base_utc_offset_delta, bool no_daylight_transitions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| date_start | DateTime | The date and time when the adjustment rule comes into effect. |
| date_end | DateTime | The date and time when the adjustment rule stops being effectvie. |
| daylight_delta | TimeSpan | The amount of time required to form the daylight saving time of the time zone. |
| daylight_transition_start | const TransitionTime\& | The information about transition from daylight saving time to standard time. |
| daylight_transition_end | const TransitionTime\& | The information about transition from standard time to daylight saving time. |
| base_utc_offset_delta | TimeSpan | The delta from the default UTC offset. |
| no_daylight_transitions | bool | Specifies wheter the adjustment rule assumes the transition to daylight saving time. |

### ReturnValue

An instance of [AdjustmentRule](../) class that represents the described time zone adjustment rule.

## See Also

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
