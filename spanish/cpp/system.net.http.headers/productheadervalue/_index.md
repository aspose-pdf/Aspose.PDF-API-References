---
title: "System::Net::Http::Headers::ProductHeaderValue clase"
linktitle: "ProductHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::ProductHeaderValue. Representa un token de producto en el valor del encabezado ''User-Agent''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1700
url: /es/cpp/system.net.http.headers/productheadervalue/
---
## ProductHeaderValue class


Representa un token de producto en el valor del encabezado 'User-Agent'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ProductHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Name](./get_name/)() | Información RTTI. |
| [get_Version](./get_version/)() | Devuelve la versión del token de producto. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetProductLength](./getproductlength/)(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [ProductHeaderValue](./). |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [ProductHeaderValue](./). |
| [ProductHeaderValue](./productheadervalue/)(String) | Construye una nueva instancia. |
| [ProductHeaderValue](./productheadervalue/)(String, String) | Construye una nueva instancia. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ProductHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [ProductHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
