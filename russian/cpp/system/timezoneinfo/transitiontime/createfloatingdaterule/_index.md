---
title: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule метод"
linktitle: "CreateFloatingDateRule"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule метод. Создаёт экземпляр класса TransitionTime, представляющий правило плавающей даты (изменение времени, происходящее в конкретный день конкретной недели конкретного месяца) в C++."
type: docs
weight: 1100
url: /ru/cpp/system/timezoneinfo/transitiontime/createfloatingdaterule/
---
## TransitionTime::CreateFloatingDateRule method


Создаёт экземпляр класса [TransitionTime](../), представляющего правило плавающей даты (изменение времени, происходящее в конкретный день конкретной недели конкретного месяца).

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule(DateTime time_of_day, int month, int week, DayOfWeek day_of_week)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| time_of_day | DateTime | Конкретное время, в которое происходит изменение времени. |
| месяц | int | Месяц года, в который происходит изменение времени. |
| неделя | int | Неделя месяца, в которую происходит изменение времени. |
| day_of_week | DayOfWeek | День недели, в который происходит изменение времени. |

### ReturnValue

Экземпляр класса [TransitionTime](../), представляющего описанное изменение времени.

## См. также

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
