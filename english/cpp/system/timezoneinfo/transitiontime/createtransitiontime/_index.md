---
title: System::TimeZoneInfo::TransitionTime::CreateTransitionTime method
linktitle: CreateTransitionTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::TransitionTime::CreateTransitionTime method. Constructs an instance of TransitionTime class that represents a time change described with the specified parameters in C++.'
type: docs
weight: 1200
url: /cpp/system/timezoneinfo/transitiontime/createtransitiontime/
---
## TransitionTime::CreateTransitionTime method


Constructs an instance of [TransitionTime](../) class that represents a time change described with the specified parameters.

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateTransitionTime(DateTime time_of_day, int month, int week, int day, DayOfWeek day_of_week, bool is_fixed_date_rule)
```


| Parameter | Type | Description |
| --- | --- | --- |
| time_of_day | DateTime | The specific time at which the time change occurs. |
| month | int | The month of the year at which the time change occurs. |
| week | int | The week of the month at which the time change occurs. |
| day | int | The day at which the time change occurs. |
| day_of_week | DayOfWeek | The day of week at which the time change occurs. |
| is_fixed_date_rule | bool | Value that indicates if the time change occurs at a fixed date and time or a floating date and time. |

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
