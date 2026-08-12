---
title: "System::Net::Http::Headers::ContentRangeHeaderValue class"
linktitle: "ContentRangeHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::ContentRangeHeaderValue class. Representa un valor del encabezado ''Content-Range''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue class


Representa un valor del encabezado 'Content-Range'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t, int64_t) | Construye una nueva instancia. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t) | Construye una nueva instancia. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t) | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_From](./get_from/)() | Obtiene una posición en la que debe comenzar el envío de datos. |
| [get_HasLength](./get_haslength/)() const | Obtiene un valor que indica si la longitud está especificada para el encabezado actual. |
| [get_HasRange](./get_hasrange/)() const | Obtiene un valor que indica si el rango está especificado para el encabezado actual. |
| [get_Length](./get_length/)() | Obtiene la longitud del cuerpo de la entidad. |
| [get_To](./get_to/)() | Obtiene una posición en la que debe detenerse el envío de datos. |
| [get_Unit](./get_unit/)() | Información RTTI. |
| static [GetContentRangeLength](./getcontentrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde la posición especificada a una instancia de la clase [ContentRangeHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [ContentRangeHeaderValue](./). |
| [set_Unit](./set_unit/)(String) | Establece las unidades usadas en el rango. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [ContentRangeHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
