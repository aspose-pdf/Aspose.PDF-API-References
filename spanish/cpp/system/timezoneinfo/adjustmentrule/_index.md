---
title: "System::TimeZoneInfo::AdjustmentRule clase"
linktitle: "AdjustmentRule"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TimeZoneInfo::AdjustmentRule clase. Proporciona información sobre un ajuste de zona horaria. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 3300
url: /es/cpp/system/timezoneinfo/adjustmentrule/
---
## AdjustmentRule class


Proporciona información sobre un ajuste de zona horaria. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class AdjustmentRule : public System::IEquatable<AdjustmentRulePtr>
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) | Construye una instancia de la clase [AdjustmentRule](./) que representa una regla de ajuste de tiempo descrita con los parámetros especificados. |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) | Construye una instancia de la clase [AdjustmentRule](./) que representa una regla de ajuste de tiempo descrita con los parámetros especificados. |
| [Equals](./equals/)(AdjustmentRulePtr) override |  |
| [get_BaseUtcOffsetDelta](./get_baseutcoffsetdelta/)() const | Devuelve una delta del desplazamiento UTC predeterminado. |
| [get_DateEnd](./get_dateend/)() const | Devuelve un objeto [DateTime](../../datetime/) que representa la fecha y hora en que la regla de ajuste deja de ser efectiva. |
| [get_DateStart](./get_datestart/)() const | Devuelve un objeto [DateTime](../../datetime/) que representa la fecha y hora en que la regla de ajuste entra en vigor. |
| [get_DaylightDelta](./get_daylightdelta/)() const | Devuelve un objeto [TimeSpan](../../timespan/) que representa la cantidad de tiempo requerida para establecer el horario de verano de la zona horaria. |
| [get_DaylightTransitionEnd](./get_daylighttransitionend/)() const | Devuelve la información sobre la transición de la hora estándar al horario de verano. |
| [get_DaylightTransitionStart](./get_daylighttransitionstart/)() const | Devuelve la información sobre la transición del horario de verano a la hora estándar. |
| [get_HasDaylightSaving](./get_hasdaylightsaving/)() const | SOLO USO INTERNO. |
| [GetHashCode](./gethashcode/)() const override | Análogo al método C# [Object.GetHashCode()](../../object/gethashcode/). Permite el hash de objetos personalizados. |
## Ver también

* Class [IEquatable](../../iequatable/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
