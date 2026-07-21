---
title: "Clase System::Net::IPAddress"
linktitle: "IPAddress"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::IPAddress. Representa la dirección IP. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2400
url: /es/cpp/system.net/ipaddress/
---
## IPAddress class


Representa la dirección IP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class IPAddress : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_AddressFamily](./get_addressfamily/)() | Devuelve la familia de direcciones. |
| [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Devuelve un valor que indica si la dirección es una dirección IPv4 y está mapeada a una dirección IPv6. |
| [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Devuelve un valor que indica si la dirección es una dirección IPv6 link-local. |
| [get_IsIPv6Multicast](./get_isipv6multicast/)() | Devuelve un valor que indica si la dirección es una dirección multicast IPv6 global. |
| [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Devuelve un valor que indica si la dirección es una dirección IPv6 site-local. |
| [get_IsIPv6Teredo](./get_isipv6teredo/)() | Devuelve un valor que indica si la dirección es una dirección IPv6 Teredo. |
| [get_ScopeId](./get_scopeid/)() | Obtiene el identificador de ámbito de la dirección IPv6. |
| [GetAddressBytes](./getaddressbytes/)() | Devuelve una matriz de bytes de la dirección IP. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [GetImpl](./getimpl/)() const | Devuelve un puntero a la implementación. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int64_t) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int32_t) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int16_t) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
| [IPAddress](./ipaddress/)(int64_t) | Construye una nueva instancia. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>, int64_t) | Construye una nueva instancia. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>) | Construye una nueva instancia. |
| [IPAddress](./ipaddress/)() | Construye una nueva instancia. |
| static [IsLoopback](./isloopback/)(System::SharedPtr\<IPAddress\>) | Devuelve un valor que indica si la dirección especificada es una dirección de loopback. |
| [MapToIPv4](./maptoipv4/)() | Mapea la dirección a la dirección IPv4. |
| [MapToIPv6](./maptoipv6/)() | Mapea la dirección a la dirección IPv6. |
| static [NetworkToHostOrder](./networktohostorder/)(int64_t) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
| static [NetworkToHostOrder](./networktohostorder/)(int32_t) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
| static [NetworkToHostOrder](./networktohostorder/)(int16_t) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [IPAddress](./). |
| [set_ScopeId](./set_scopeid/)(int64_t) | Establece el identificador de ámbito de la dirección IPv6. |
| [SetImpl](./setimpl/)(ImplPtr) | Establece un puntero a la implementación. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<IPAddress\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [IPAddress](./). |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Any](./any/) | Información RTTI. |
| static [Broadcast](./broadcast/) | La dirección de broadcast IPv4. |
| static [IPv6Any](./ipv6any/) | La dirección IPv6 que indica si el servidor debe escuchar todas las interfaces de red. |
| static [IPv6Loopback](./ipv6loopback/) | La dirección IPv6 de loopback. |
| static [IPv6None](./ipv6none/) | La dirección IPv6 que indica si el servidor no debe escuchar ninguna interfaz de red. |
| static [Loopback](./loopback/) | La dirección IPv4 de loopback. |
| static [None](./none/) | La dirección IPv4 que indica si el servidor no debe escuchar ninguna interfaz de red. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ImplPtr](./implptr/) | Un puntero al tipo de implementación. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
