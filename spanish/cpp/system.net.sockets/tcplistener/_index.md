---
title: "System::Net::Sockets::TcpListener clase"
linktitle: "TcpListener"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::TcpListener clase. Representa un escuchador para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.net.sockets/tcplistener/
---
## TcpListener class


Representa un escuchador para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class TcpListener : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AcceptSocket](./acceptsocket/)() | Acepta la solicitud de conexión pendiente y devuelve el socket que se usa para enviar y recibir datos. |
| [AcceptTcpClient](./accepttcpclient/)() | Acepta la solicitud de conexión pendiente y devuelve la instancia de la clase TcpClient que se usa para enviar y recibir datos. |
| [AllowNatTraversal](./allownattraversal/)(bool) | Habilita o deshabilita la traversía NAT. |
| [BeginAcceptSocket](./beginacceptsocket/)(AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de aceptación asíncrona. |
| [BeginAcceptTcpClient](./beginaccepttcpclient/)(AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de aceptación asíncrona. |
| static [Create](./create/)(int32_t) | Crea una nueva instancia usando el número de puerto especificado. |
| [EndAcceptSocket](./endacceptsocket/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de aceptación asíncrona especificada se complete. |
| [EndAcceptTcpClient](./endaccepttcpclient/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de aceptación asíncrona especificada se complete. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Obtiene un valor que indica si la instancia actual permite que solo un cliente use un puerto. |
| [get_LocalEndpoint](./get_localendpoint/)() | Devuelve el punto final subyacente. |
| [get_Server](./get_server/)() | Información RTTI. |
| [Pending](./pending/)() | Devuelve un valor que indica si hay solicitudes de conexión pendientes. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Establece un valor que indica si la instancia actual permite que solo un cliente use un puerto. |
| [Start](./start/)() | Inicia la escucha de las conexiones entrantes. |
| [Start](./start/)(int32_t) | Inicia la escucha de las conexiones entrantes. |
| [Stop](./stop/)() | Detiene la escucha de las conexiones entrantes. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPEndPoint\>) | Construye una nueva instancia. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPAddress\>, int32_t) | Construye una nueva instancia. |
| [TcpListener](./tcplistener/)(int32_t) | Construye una nueva instancia. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
