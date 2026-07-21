---
title: "Clase System::Net::DnsEndPoint"
linktitle: "DnsEndPoint"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::DnsEndPoint. Contiene información utilizada por la aplicación para conectarse al servicio. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.net/dnsendpoint/
---
## DnsEndPoint class


Contiene información utilizada por la aplicación para conectarse al servicio. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class DnsEndPoint : public System::Net::EndPoint
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t) | Construye una nueva instancia. |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t, System::Net::Sockets::AddressFamily) | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_AddressFamily](./get_addressfamily/)() override | Información RTTI. |
| [get_Host](./get_host/)() | Información RTTI. |
| [get_Port](./get_port/)() | Devuelve el número de puerto. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
