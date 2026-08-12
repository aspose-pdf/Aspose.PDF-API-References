---
title: "Clase System::Net::Http::Headers::RangeConditionHeaderValue"
linktitle: "RangeConditionHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::RangeConditionHeaderValue. Representa un valor del encabezado ''If-Range''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1900
url: /es/cpp/system.net.http.headers/rangeconditionheadervalue/
---
## RangeConditionHeaderValue class


Representa un valor del encabezado 'If-Range'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class RangeConditionHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Date](./get_date/)() | Información RTTI. |
| [get_EntityTag](./get_entitytag/)() | Devuelve el valor del encabezado 'ETag'. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetRangeConditionLength](./getrangeconditionlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [RangeConditionHeaderValue](./). |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [RangeConditionHeaderValue](./). |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(DateTimeOffset) | Construye una nueva instancia. |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(System::SharedPtr\<EntityTagHeaderValue\>) | Construye una nueva instancia. |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(String) | Construye una nueva instancia. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RangeConditionHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [RangeConditionHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
