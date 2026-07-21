---
title: "Clase System::TimeZone"
linktitle: "TimeZone"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::TimeZone. Representa una zona horaria. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 6500
url: /es/cpp/system/timezone/
---
## TimeZone class


Representa una zona horaria. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class TimeZone : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [get_CurrentTimeZone](./get_currenttimezone/)() | Devuelve una nueva instancia de la clase [TimeZone](./) que representa la zona horaria actual. |
| virtual [get_DaylightName](./get_daylightname/)() const | Devuelve un nombre para el horario de verano de la zona horaria representada por el objeto actual. |
| virtual [get_StandardName](./get_standardname/)() const | Devuelve un nombre para el horario estándar de la zona horaria representada por el objeto actual. |
| virtual [GetDaylightChanges](./getdaylightchanges/)(int32_t) | Devuelve el período de horario de verano para un año determinado. |
| virtual [GetUtcOffset](./getutcoffset/)(DateTime) | Devuelve el desplazamiento UTC para la hora local especificada. |
| virtual [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) | Determina si el valor de fecha y hora representado por el objeto [DateTime](../datetime/) especificado se encuentra dentro del rango de horario de verano para la zona horaria representada por el objeto [TimeZone](./) actual. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
