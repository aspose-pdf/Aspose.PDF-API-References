---
title: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule método"
linktitle: "CreateAdjustmentRule"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule método. Construye una instancia de la clase AdjustmentRule que representa una regla de ajuste de hora descrita con los parámetros especificados en C++."
type: docs
weight: 1000
url: /es/cpp/system/timezoneinfo/adjustmentrule/createadjustmentrule/
---
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) method


Construye una instancia de la clase [AdjustmentRule](../) que representa una regla de ajuste de hora descrita con los parámetros especificados.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_start | DateTime | La fecha y hora en que la regla de ajuste entra en vigor. |
| date_end | DateTime | La fecha y hora en que la regla de ajuste deja de estar vigente. |
| daylight_delta | TimeSpan | La cantidad de tiempo requerida para establecer el horario de verano de la zona horaria. |
| daylight_transition_start | const TransitionTime\& | La información sobre la transición del horario de verano al horario estándar. |
| daylight_transition_end | const TransitionTime\& | La información sobre la transición del horario estándar al horario de verano. |

### ReturnValue

Una instancia de la clase [AdjustmentRule](../) que representa la regla de ajuste de zona horaria descrita.

## Ver también

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) method


Construye una instancia de la clase [AdjustmentRule](../) que representa una regla de ajuste de hora descrita con los parámetros especificados.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end, TimeSpan base_utc_offset_delta, bool no_daylight_transitions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_start | DateTime | La fecha y hora en que la regla de ajuste entra en vigor. |
| date_end | DateTime | La fecha y hora en que la regla de ajuste deja de estar vigente. |
| daylight_delta | TimeSpan | La cantidad de tiempo requerida para establecer el horario de verano de la zona horaria. |
| daylight_transition_start | const TransitionTime\& | La información sobre la transición del horario de verano al horario estándar. |
| daylight_transition_end | const TransitionTime\& | La información sobre la transición del horario estándar al horario de verano. |
| base_utc_offset_delta | TimeSpan | El delta desde el desplazamiento UTC predeterminado. |
| no_daylight_transitions | bool | Especifica si la regla de ajuste asume la transición al horario de verano. |

### ReturnValue

Una instancia de la clase [AdjustmentRule](../) que representa la regla de ajuste de zona horaria descrita.

## Ver también

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PDF for C++](../../../../)
