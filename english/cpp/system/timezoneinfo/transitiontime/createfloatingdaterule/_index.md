---
title: System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule method
linktitle: CreateFloatingDateRule
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule method. Constructs an instance of TransitionTime class that represents a floating-date rule (time change that occurs on specific day of a specific week of a specific month) in C++.'
type: docs
weight: 1100
url: /cpp/system/timezoneinfo/transitiontime/createfloatingdaterule/
---
## TransitionTime::CreateFloatingDateRule method


Constructs an instance of [TransitionTime](../) class that represents a floating-date rule (time change that occurs on specific day of a specific week of a specific month).

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule(DateTime time_of_day, int month, int week, DayOfWeek day_of_week)
```


| Parameter | Type | Description |
| --- | --- | --- |
| time_of_day | DateTime | The specific time at which the time change occurs. |
| month | int | The month of the year at which the time change occurs. |
| week | int | The week of the month at which the time change occurs. |
| day_of_week | DayOfWeek | The day of week at which the time change occurs. |

### ReturnValue

An istance of [TransitionTime](../) class that represents the described time change.

## See Also

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
