---
title: "Clase System::Net::IPEndPoint"
linktitle: "IPEndPoint"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::IPEndPoint. Representa un punto de red que contiene una dirección IP y un puerto. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2500
url: /es/cpp/system.net/ipendpoint/
---
## IPEndPoint class


Representa un punto de red que contiene una dirección IP y un puerto. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class IPEndPoint : public System::Net::EndPoint
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Create](./create/)(System::SharedPtr\<SocketAddress\>) override | Cree una nueva instancia de la clase [EndPoint](../endpoint/) usando la dirección de socket especificada. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Address](./get_address/)() | Obtiene la dirección del punto final. |
| [get_AddressFamily](./get_addressfamily/)() override | Información RTTI. |
| [get_Port](./get_port/)() | Obtiene el número de puerto. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [GetImpl](./getimpl/)() const override | Devuelve un puntero a la implementación. |
| [IPEndPoint](./ipendpoint/)(int64_t, int32_t) | Construye una nueva instancia. |
| [IPEndPoint](./ipendpoint/)(System::SharedPtr\<IPAddress\>, int32_t) | Construye una nueva instancia. |
| [set_Address](./set_address/)(System::SharedPtr\<IPAddress\>) | Establece la dirección del punto final. |
| [set_Port](./set_port/)(int32_t) | Establece el número de puerto. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Any](./any/) | El punto final para cualquier dirección IPv4 y cualquier puerto. |
| static [AnyPort](./anyport/) | Un valor que indica si se puede usar cualquier puerto. |
| static [IPv6Any](./ipv6any/) | El punto final para cualquier dirección IPv6 y cualquier puerto. |
| static [MaxPort](./maxport/) | El número máximo de puerto. |
| static [MinPort](./minport/) | Información RTTI. |
## Ver también

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
