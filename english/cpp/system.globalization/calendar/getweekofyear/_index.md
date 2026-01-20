---
title: System::Globalization::Calendar::GetWeekOfYear method
linktitle: GetWeekOfYear
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::Calendar::GetWeekOfYear method. Gets week of the year for the specified time point in C++.'
type: docs
weight: 3200
url: /cpp/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear method


Gets week of the year for the specified time point.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| time | DateTime | Time and date to extract data from. |
| rule | CalendarWeekRule | Determines how to determine the first week of the year. |
| first_day_of_week | DayOfWeek | Determines first day of week. |

### ReturnValue

Year week number in the time point passed.

## See Also

* Class [DateTime](../../../system/datetime/)
* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
