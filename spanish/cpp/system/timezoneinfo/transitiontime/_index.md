---
title: "System::TimeZoneInfo::TransitionTime class"
linktitle: "TransitionTime"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TimeZoneInfo::TransitionTime class. Información RTTI en C++."
type: docs
weight: 3400
url: /es/cpp/system/timezoneinfo/transitiontime/
---
## TransitionTime class


Información RTTI.

```cpp
class TransitionTime
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateFixedDateRule](./createfixeddaterule/)(DateTime, int, int) | Construye una instancia de la clase [TransitionTime](./) que representa una regla de fecha fija (cambio de hora que ocurre en un día específico de un mes específico). |
| static [CreateFloatingDateRule](./createfloatingdaterule/)(DateTime, int, int, DayOfWeek) | Construye una instancia de la clase [TransitionTime](./) que representa una regla de fecha flotante (cambio de hora que ocurre en un día específico de una semana específica de un mes específico). |
| static [CreateTransitionTime](./createtransitiontime/)(DateTime, int, int, int, DayOfWeek, bool) | Construye una instancia de la clase [TransitionTime](./) que representa un cambio de hora descrito con los parámetros especificados. |
| [get_Day](./get_day/)() const | Devuelve el número ordinal del día de la semana en el que ocurre el cambio de hora. |
| [get_DayOfWeek](./get_dayofweek/)() const | Devuelve el valor que representa el día de la semana en el que ocurre el cambio de hora. |
| [get_IsFixedDateRule](./get_isfixeddaterule/)() const | Devuelve el valor que indica si el cambio de hora ocurre en una fecha y hora fijas o en una fecha y hora flotantes. |
| [get_Month](./get_month/)() const | Devuelve el número ordinal del mes del año en el que ocurre el cambio de hora. |
| [get_TimeOfDay](./get_timeofday/)() const | Devuelve un objeto [DateTime](../../datetime/) que representa la hora específica en la que ocurre el cambio de hora. |
| [get_Week](./get_week/)() const | Devuelve el número ordinal de la semana del mes en el que ocurre el cambio de hora. |
| [operator!=](./operator!=/)(const TransitionTime\&) const |  |
| [operator==](./operator==/)(const TransitionTime\&) const |  |
| [TransitionTime](./transitiontime/)() | Constructor predeterminado. USO INTERNO. |
## Observaciones


Proporciona información sobre un cambio de hora en una zona horaria.
## Ver también

* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
