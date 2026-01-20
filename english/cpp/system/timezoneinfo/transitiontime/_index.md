---
title: System::TimeZoneInfo::TransitionTime class
linktitle: TransitionTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::TransitionTime class. RTTI information in C++.'
type: docs
weight: 3400
url: /cpp/system/timezoneinfo/transitiontime/
---
## TransitionTime class


RTTI information.

```cpp
class TransitionTime
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateFixedDateRule](./createfixeddaterule/)(DateTime, int, int) | Constructs an instance of [TransitionTime](./) class that represents a fixed-date rule (time change that occurs on specific day of a specific month). |
| static [CreateFloatingDateRule](./createfloatingdaterule/)(DateTime, int, int, DayOfWeek) | Constructs an instance of [TransitionTime](./) class that represents a floating-date rule (time change that occurs on specific day of a specific week of a specific month). |
| static [CreateTransitionTime](./createtransitiontime/)(DateTime, int, int, int, DayOfWeek, bool) | Constructs an instance of [TransitionTime](./) class that represents a time change described with the specified parameters. |
| [get_Day](./get_day/)() const | Returns the ordinal number of the day of week at which the time change occurs. |
| [get_DayOfWeek](./get_dayofweek/)() const | Returns the value that represents the day of week at which the time change occurs. |
| [get_IsFixedDateRule](./get_isfixeddaterule/)() const | Returns the value that indicates if the time change occurs at a fixed date and time or a floating date and time. |
| [get_Month](./get_month/)() const | Returns the ordinal number of the month of the year at which the time change occurs. |
| [get_TimeOfDay](./get_timeofday/)() const | Returns a [DateTime](../../datetime/) object that represents the specific time at which the time change occurs. |
| [get_Week](./get_week/)() const | Returns the ordinal number of the week of the month at which the time change occurs. |
| [operator!=](./operator!=/)(const TransitionTime\&) const |  |
| [operator==](./operator==/)(const TransitionTime\&) const |  |
| [TransitionTime](./transitiontime/)() | Default constructor. FOR INTERNAL USE. |
## Remarks


Provides information about a time change in a time zone. 
## See Also

* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
