---
title: "System::Globalization::Calendar::GetWeekOfYear метод"
linktitle: "GetWeekOfYear"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::Calendar::GetWeekOfYear метод. Получает номер недели года для указанного момента времени в C++."
type: docs
weight: 3200
url: /ru/cpp/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear method


Получает номер недели в году для указанного момента времени.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| время | DateTime | Время и дата, из которых нужно извлечь данные. |
| правило | CalendarWeekRule | Определяет, как определить первую неделю года. |
| first_day_of_week | DayOfWeek | Определяет первый день недели. |

### ReturnValue

Номер недели года в переданном моменте времени.

## См. также

* Class [DateTime](../../../system/datetime/)
* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
