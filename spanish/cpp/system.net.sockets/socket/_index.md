---
title: "System::Net::Sockets::Socket clase"
linktitle: "Socket"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket clase. La clase Socket implementa la interfaz de sockets Berkeley en C++."
type: docs
weight: 400
url: /es/cpp/system.net.sockets/socket/
---
## Socket class


La clase [Socket](./) implementa la interfaz de sockets Berkeley.

```cpp
class Socket : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)() | Crea un nuevo socket para la conexión recién creada. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginReceive](./beginreceive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de escritura asíncrona. |
| [BeginSend](./beginsend/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de envío asíncrona. |
| [Bind](./bind/)(System::SharedPtr\<EndPoint\>) | Asocia el socket con el punto final local especificado. |
| [Close](./close/)() | Cierra la conexión del socket. |
| [Close](./close/)(int) | Cierra la conexión del socket con el tiempo de espera especificado para permitir que se envíen los datos en cola. |
| [Connect](./connect/)(System::SharedPtr\<EndPoint\>) | Establece una conexión al punto final remoto especificado. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establece una conexión al punto final remoto especificado. |
| [Connect](./connect/)(String, int32_t) | Establece una conexión al punto final remoto especificado. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Establece una conexión al punto final remoto especificado. |
| [Dispose](./dispose/)() override | No hace nada. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de conexión asíncrona especificada se complete. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de recepción asíncrona especificada se complete. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Espera hasta que la operación de recepción asíncrona especificada se complete. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de envío asíncrona especificada se complete. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Espera hasta que la operación de envío asíncrona especificada se complete. |
| [get_AddressFamily](./get_addressfamily/)() | Devuelve la familia de direcciones. |
| [get_Available](./get_available/)() | Obtiene el número de bytes recibidos de la red y disponibles para leer. |
| [get_Blocking](./get_blocking/)() | Obtiene un valor que indica si el socket está en modo bloqueante. |
| [get_Connected](./get_connected/)() | Devuelve un valor que indica si el socket está conectado al host remoto. |
| [get_DontFragment](./get_dontfragment/)() | Obtiene un valor que indica si el socket permite que los datagramas IP se fragmenten. |
| [get_DualMode](./get_dualmode/)() | Obtiene un valor que indica si el socket está en modo dual. |
| [get_EnableBroadcast](./get_enablebroadcast/)() | Obtiene un valor que indica si el socket permite paquetes de difusión. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Obtiene un valor que indica si solo un proceso puede asociar el socket a un puerto. |
| [get_IsBound](./get_isbound/)() | Devuelve un valor que indica si el socket está asociado a un puerto local específico. |
| [get_LingerState](./get_lingerstate/)() | Obtiene un valor que indica si el socket retrasará el cierre en un intento de enviar todos los datos pendientes. |
| [get_LocalEndPoint](./get_localendpoint/)() | Devuelve el punto final local. |
| [get_MulticastLoopback](./get_multicastloopback/)() | Obtiene un valor que indica si el socket recibe paquetes multicast salientes. |
| [get_NoDelay](./get_nodelay/)() | Obtiene un valor que indica si el socket está usando el algoritmo Nagle. |
| static [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Devuelve un valor que indica si el sistema operativo y los adaptadores de red admiten IPv4. |
| static [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Devuelve un valor que indica si el sistema operativo y los adaptadores de red admiten IPv6. |
| [get_ProtocolType](./get_protocoltype/)() | Devuelve el tipo de protocolo. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Obtiene el tamaño del búfer de recepción. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Obtiene un período después del cual una llamada 'Receive' expirará. |
| [get_RemoteEndPoint](./get_remoteendpoint/)() | Devuelve el punto final remoto. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Obtiene el tamaño del búfer de envío. |
| [get_SendTimeout](./get_sendtimeout/)() | Obtiene un período después del cual una llamada 'Send' expirará. |
| [get_SocketType](./get_sockettype/)() | Devuelve el tipo de socket. |
| static [get_SupportsIPv4](./get_supportsipv4/)() | Información RTTI. |
| [get_Ttl](./get_ttl/)() | Obtiene el valor TTL. |
| [GetImpl](./getimpl/)() const | Devuelve un puntero a la implementación. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName) | Devuelve el valor que corresponde al nombre de opción especificado. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Obtiene el valor que corresponde al nombre de opción especificado. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Devuelve el valor que corresponde al nombre de opción especificado. |
| [IOControl](./iocontrol/)(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Establece modos de operación de bajo nivel para el socket. |
| [IOControl](./iocontrol/)(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Establece modos de operación de bajo nivel para el socket. |
| [Listen](./listen/)(int32_t) | Cambia el estado del socket a 'listen'. |
| [Poll](./poll/)(int32_t, SelectMode) | Devuelve el estado del socket basado en el modo de sondeo especificado. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Recibe datos del socket y los escribe en la matriz de bytes especificada. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Recibe datos del socket y los escribe en las matrices de bytes especificadas. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Recibe datos del socket y los escribe en las matrices de bytes especificadas. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Recibe datos del socket y los escribe en las matrices de bytes especificadas. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&) | Envía los datos especificados al socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Envía los datos especificados al socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Envía los datos especificados al socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Envía los datos especificados al socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Envía los datos especificados al socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Envía los datos especificados al socket. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) | Envía los datos especificados al punto final especificado. |
| [set_Blocking](./set_blocking/)(bool) | Establece un valor que indica si el socket está en modo de bloqueo. |
| [set_ConnectionTimeout](./set_connectiontimeout/)(int32_t) | Establece el tiempo de espera de la conexión. |
| [set_DontFragment](./set_dontfragment/)(bool) | Establece un valor que indica si el socket permite que los datagramas IP se fragmenten. |
| [set_DualMode](./set_dualmode/)(bool) | Establece un valor que indica si el socket está en modo dual. |
| [set_EnableBroadcast](./set_enablebroadcast/)(bool) | Establece un valor que indica si el socket permite paquetes de difusión. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Establece un valor que indica si solo un proceso puede enlazar el socket a un puerto. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Establece un valor que indica si el socket retrasará el cierre en un intento de enviar todos los datos pendientes. |
| [set_MulticastLoopback](./set_multicastloopback/)(bool) | Establece un valor que indica si el socket recibe paquetes multicast salientes. |
| [set_NoDelay](./set_nodelay/)(bool) | Establece un valor que indica si el socket está usando el algoritmo Nagle. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Establece el tamaño del búfer de recepción. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Establece un período después del cual una llamada 'Receive' expirará. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Establece el tamaño del búfer de envío. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Establece un período después del cual una llamada 'Send' expirará. |
| [set_Ttl](./set_ttl/)(int16_t) | Establece el valor TTL. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Establece la opción de socket especificada al valor especificado. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Establece la opción de socket especificada al valor especificado. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, bool) | Establece la opción de socket especificada al valor especificado. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) | Establece la opción de socket especificada al valor especificado. |
| [Shutdown](./shutdown/)(SocketShutdown) | Desactiva las operaciones de envío y recepción del socket. |
| [Socket](./socket/)(System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Construye una nueva instancia. |
| [Socket](./socket/)(System::Net::Sockets::AddressFamily, System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Construye una nueva instancia. |
| virtual [~Socket](./~socket/)() | Destruye la instancia actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ImplPtr](./implptr/) | La implementación del socket. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
