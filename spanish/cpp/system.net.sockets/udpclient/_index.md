---
title: "Clase System::Net::Sockets::UdpClient"
linktitle: "UdpClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Sockets::UdpClient. Proporciona servicios de red del Protocolo de Datagramas de Usuario (UDP). Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.net.sockets/udpclient/
---
## UdpClient class


Proporciona servicios de red del Protocolo de Datagramas de Usuario (UDP). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class UdpClient : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() | Cierra la conexión UDP. |
| [Connect](./connect/)(String, int32_t) | Establece una conexión al puerto especificado en el host especificado. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establece una conexión con el host en la dirección especificada y el puerto especificado. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Establece una conexión a un punto final remoto. |
| [Dispose](./dispose/)() override | Libera los recursos administrados y no administrados utilizados por el [UdpClient](./). |
| [get_Client](./get_client/)() | Información RTTI. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Devuelve un datagrama enviado por un servidor. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Envía un datagrama UDP al host en el punto final remoto. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Envía un datagrama UDP al puerto especificado en el host remoto especificado. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Envía un datagrama UDP a un host remoto. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Se utiliza para proporcionar el socket de red subyacente. |
| [UdpClient](./udpclient/)() | Inicializa una nueva instancia de la clase [UdpClient](./). |
| [UdpClient](./udpclient/)(AddressFamily) | Inicializa una nueva instancia de la clase [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t) | Inicializa una nueva instancia de la clase [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | Inicializa una nueva instancia de la clase [UdpClient](./). |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | Inicializa una nueva instancia de la clase [UdpClient](./). param local EP el punto final local al que enlaza la conexión UDP. |
| [UdpClient](./udpclient/)(String, int32_t) | Crea una nueva instancia de la clase [UdpClient](./) y se conecta al host remoto especificado en el puerto especificado. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
