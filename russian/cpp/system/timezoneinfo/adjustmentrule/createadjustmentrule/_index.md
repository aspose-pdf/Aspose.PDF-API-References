---
title: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule метод"
linktitle: "CreateAdjustmentRule"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule метод. Создаёт экземпляр класса AdjustmentRule, представляющего правило корректировки времени, описанное с указанными параметрами в C++."
type: docs
weight: 1000
url: /ru/cpp/system/timezoneinfo/adjustmentrule/createadjustmentrule/
---
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) method


Создаёт экземпляр класса [AdjustmentRule](../), представляющего правило корректировки времени, описанное с указанными параметрами.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| date_start | DateTime | Дата и время, когда правило корректировки вступает в силу. |
| date_end | DateTime | Дата и время, когда правило корректировки перестаёт действовать. |
| daylight_delta | TimeSpan | Величина времени, необходимая для формирования летнего времени часового пояса. |
| daylight_transition_start | const TransitionTime\& | Информация о переходе от летнего времени к стандартному времени. |
| daylight_transition_end | const TransitionTime\& | Информация о переходе от стандартного времени к летнему времени. |

### ReturnValue

Экземпляр класса [AdjustmentRule](../), представляющего описанное правило корректировки часового пояса.

## См. также

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) method


Создаёт экземпляр класса [AdjustmentRule](../), представляющего правило корректировки времени, описанное с указанными параметрами.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end, TimeSpan base_utc_offset_delta, bool no_daylight_transitions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| date_start | DateTime | Дата и время, когда правило корректировки вступает в силу. |
| date_end | DateTime | Дата и время, когда правило корректировки перестаёт действовать. |
| daylight_delta | TimeSpan | Величина времени, необходимая для формирования летнего времени часового пояса. |
| daylight_transition_start | const TransitionTime\& | Информация о переходе от летнего времени к стандартному времени. |
| daylight_transition_end | const TransitionTime\& | Информация о переходе от стандартного времени к летнему времени. |
| base_utc_offset_delta | TimeSpan | Изменение относительно стандартного смещения UTC. |
| no_daylight_transitions | bool | Указывает, предполагает ли правило корректировки переход к летнему времени. |

### ReturnValue

Экземпляр класса [AdjustmentRule](../), представляющего описанное правило корректировки часового пояса.

## См. также

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
