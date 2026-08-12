---
title: "Clase System::Net::Http::Headers::RangeHeaderValue"
linktitle: "RangeHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::RangeHeaderValue. Representa un valor del encabezado ''Range''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.net.http.headers/rangeheadervalue/
---
## RangeHeaderValue class


Representa un valor del encabezado '[Range](../../system/range/)'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class RangeHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Ranges](./get_ranges/)() | Devuelve la colección de los rangos. |
| [get_Unit](./get_unit/)() | Información RTTI. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetRangeLength](./getrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [RangeHeaderValue](./). |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [RangeHeaderValue](./). |
| [RangeHeaderValue](./rangeheadervalue/)() | Construye una nueva instancia. |
| [RangeHeaderValue](./rangeheadervalue/)(Nullable\<int64_t\>, Nullable\<int64_t\>) | Construye una nueva instancia. |
| [set_Unit](./set_unit/)(String) | Establece una unidad. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RangeHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [RangeHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
