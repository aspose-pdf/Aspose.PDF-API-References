---
title: "Clase System::Net::Http::Headers::ViaHeaderValue"
linktitle: "ViaHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::ViaHeaderValue. Representa un valor del encabezado ''Via''. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system.net.http.headers/viaheadervalue/
---
## ViaHeaderValue class


Representa un valor del encabezado 'Via'. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class ViaHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Comment](./get_comment/)() | Devuelve el comentario del valor del encabezado 'Via'. |
| [get_ProtocolName](./get_protocolname/)() | Información RTTI. |
| [get_ProtocolVersion](./get_protocolversion/)() | Devuelve la versión del protocolo del valor del encabezado 'Via'. |
| [get_ReceivedBy](./get_receivedby/)() | Devuelve el host y el puerto a los que se recibió la solicitud o respuesta. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetViaLength](./getvialength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado en una instancia de la clase [ViaHeaderValue](./). |
| static [Parse](./parse/)(String) | Convierte una cadena pasada en una instancia de la clase [ViaHeaderValue](./). |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ViaHeaderValue\>\&) | Intenta convertir una cadena pasada en una instancia de la clase [ViaHeaderValue](./). |
| [ViaHeaderValue](./viaheadervalue/)(String, String) | Construye una nueva instancia. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String) | Construye una nueva instancia. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String, String) | Construye una nueva instancia. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
