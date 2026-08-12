---
title: "System::TimeZoneInfo::TransitionTime::CreateTransitionTime método"
linktitle: "CreateTransitionTime"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TimeZoneInfo::TransitionTime::CreateTransitionTime método. Construye una instancia de la clase TransitionTime que representa un cambio de hora descrito con los parámetros especificados en C++."
type: docs
weight: 1200
url: /es/cpp/system/timezoneinfo/transitiontime/createtransitiontime/
---
## TransitionTime::CreateTransitionTime method


Construye una instancia de la clase [TransitionTime](../) que representa un cambio de hora descrito con los parámetros especificados.

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateTransitionTime(DateTime time_of_day, int month, int week, int day, DayOfWeek day_of_week, bool is_fixed_date_rule)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time_of_day | DateTime | La hora específica en la que ocurre el cambio de hora. |
| month | int | El mes del año en el que ocurre el cambio de hora. |
| week | int | La semana del mes en la que ocurre el cambio de hora. |
| día | int | El día en el que ocurre el cambio de hora. |
| day_of_week | DayOfWeek | El día de la semana en el que ocurre el cambio de hora. |
| is_fixed_date_rule | bool | Valor que indica si el cambio de hora ocurre en una fecha y hora fijas o en una fecha y hora flotantes. |

### ReturnValue

Una instancia de la clase [TransitionTime](../) que representa el cambio de hora descrito.

## Ver también

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
