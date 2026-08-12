---
title: "System::Net::Http::Headers::EntityTagHeaderValue class"
linktitle: "EntityTagHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::EntityTagHeaderValue class. Representa un valor del encabezado ''Entity-Tag''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.net.http.headers/entitytagheadervalue/
---
## EntityTagHeaderValue class


Representa un valor del encabezado 'Entity-Tag'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EntityTagHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String) | Construye una nueva instancia. |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String, bool) | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static [get_Any](./get_any/)() | Obtiene un valor del encabezado 'ETag'. |
| [get_IsWeak](./get_isweak/)() | Obtiene un valor que indica si la instancia actual es un validador débil. |
| [get_Tag](./get_tag/)() | Información RTTI. |
| static [GetEntityTagLength](./getentitytaglength/)(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [EntityTagHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [EntityTagHeaderValue](./). |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<EntityTagHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [EntityTagHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
