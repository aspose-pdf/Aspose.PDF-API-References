---
title: "Clase System::Net::SocketAddress"
linktitle: "SocketAddress"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::SocketAddress. Se utiliza para almacenar información serializada sobre las instancias de la clase EndPoint. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 3300
url: /es/cpp/system.net/socketaddress/
---
## SocketAddress class


Se utiliza para almacenar información serializada sobre las instancias de la clase [EndPoint](../endpoint/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class SocketAddress : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Family](./get_family/)() | Información RTTI. |
| [get_Size](./get_size/)() | Devuelve el tamaño del búfer subyacente. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [idx_get](./idx_get/)(int32_t) | Obtiene un valor del búfer subyacente en el índice especificado. |
| [idx_set](./idx_set/)(int32_t, uint8_t) | Establece un valor en el búfer subyacente en el índice especificado. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily) | Construye una nueva instancia. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily, int32_t) | Construye una nueva instancia. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
