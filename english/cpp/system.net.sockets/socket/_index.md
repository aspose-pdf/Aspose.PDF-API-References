---
title: System::Net::Sockets::Socket class
linktitle: Socket
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket class. The Socket class implements the Berkeley sockets interface in C++.'
type: docs
weight: 400
url: /cpp/system.net.sockets/socket/
---
## Socket class


The [Socket](./) class implements the Berkeley sockets interface.

```cpp
class Socket : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)() | Creates a new socket for the newly created connection. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginReceive](./beginreceive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous write operation. |
| [BeginSend](./beginsend/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous send operation. |
| [Bind](./bind/)(System::SharedPtr\<EndPoint\>) | Binds the socket with to the specified local endpoint. |
| [Close](./close/)() | Closes the socket connection. |
| [Close](./close/)(int) | Closes the socket connection with the specified timeout to allow queued data to be sent. |
| [Connect](./connect/)(System::SharedPtr\<EndPoint\>) | Establishes a connection to the specified remote endpoint. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establishes a connection to the specified remote endpoint. |
| [Connect](./connect/)(String, int32_t) | Establishes a connection to the specified remote endpoint. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Establishes a connection to the specified remote endpoint. |
| [Dispose](./dispose/)() override | Does nothing. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous connect operation completes. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous receive operation completes. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Waits until the specified asynchronous receive operation completes. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous send operation completes. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Waits until the specified asynchronous send operation completes. |
| [get_AddressFamily](./get_addressfamily/)() | Returns the address family. |
| [get_Available](./get_available/)() | Gets the number of bytes received from the network and available for reading. |
| [get_Blocking](./get_blocking/)() | Gets a value that indicates if the socket is in the blocking mode. |
| [get_Connected](./get_connected/)() | Returns a value that indicates if the socket is connected to the remote host. |
| [get_DontFragment](./get_dontfragment/)() | Gets a value that indicates if the socket allows IP datagrams to be fragmented. |
| [get_DualMode](./get_dualmode/)() | Gets a value indicates if the socket is in the dual-mode. |
| [get_EnableBroadcast](./get_enablebroadcast/)() | Gets a value that indicates if the socket allows broadcast packets. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Gets a value that indicates if only one process can bind the socket to a port. |
| [get_IsBound](./get_isbound/)() | Returns a value that indicates if the socket is bound to a specific local port. |
| [get_LingerState](./get_lingerstate/)() | Gets a value that indicates if the socket will delay closing in an attempt to send all pending data. |
| [get_LocalEndPoint](./get_localendpoint/)() | Returns the local endpoint. |
| [get_MulticastLoopback](./get_multicastloopback/)() | Gets a value that indicates if the socket receives outgoing multicast packets. |
| [get_NoDelay](./get_nodelay/)() | Gets a value that indicates if the socket is using the Nagle algorithm. |
| static [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Returns a value that indicates if the operating system and network adaptors support IPv4. |
| static [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Returns a value that indicates if the operating system and network adaptors support IPv6. |
| [get_ProtocolType](./get_protocoltype/)() | Returns the protocol type. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Gets the receive buffer size. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Gets a period after which a 'Receive' call will time out. |
| [get_RemoteEndPoint](./get_remoteendpoint/)() | Returns the remote endpoint. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Gets the send buffer size. |
| [get_SendTimeout](./get_sendtimeout/)() | Gets a period after which a 'Send' call will time out. |
| [get_SocketType](./get_sockettype/)() | Returns the socket type. |
| static [get_SupportsIPv4](./get_supportsipv4/)() | RTTI information. |
| [get_Ttl](./get_ttl/)() | Gets the TTL value. |
| [GetImpl](./getimpl/)() const | Returns a pointer to implementation. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName) | Returns the value that corresponds to the specified option name. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Gets the value that corresponds to the specified option name. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Returns the value that corresponds to the specified option name. |
| [IOControl](./iocontrol/)(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Sets low-level operating modes for the socket. |
| [IOControl](./iocontrol/)(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Sets low-level operating modes for the socket. |
| [Listen](./listen/)(int32_t) | Changes the socket state to 'listen'. |
| [Poll](./poll/)(int32_t, SelectMode) | Returns the status of the socket based on the specified polling mode. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Receives data from the socket and writes it to the specified byte array. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Receives data from the socket and writes it to the specified byte arrays. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Receives data from the socket and writes it to the specified byte arrays. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Receives data from the socket and writes it to the specified byte arrays. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Receives data from the specified endpoint and writes it to the specified byte array. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&) | Sends the specified data to the socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Sends the specified data to the socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Sends the specified data to the socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Sends the specified data to the socket. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Sends the specified data to the socket. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Sends the specified data to the socket. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) | Sends the specified data to the specified endpoint. |
| [set_Blocking](./set_blocking/)(bool) | Sets a value that indicates if the socket is in the blocking mode. |
| [set_ConnectionTimeout](./set_connectiontimeout/)(int32_t) | Sets the connection timeout. |
| [set_DontFragment](./set_dontfragment/)(bool) | Sets a value that indicates if the socket allows IP datagrams to be fragmented. |
| [set_DualMode](./set_dualmode/)(bool) | Sets a value indicates if the socket is in the dual-mode. |
| [set_EnableBroadcast](./set_enablebroadcast/)(bool) | Sets a value that indicates if the socket allows broadcast packets. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Sets a value that indicates if only one process can bind the socket to a port. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Sets a value that indicates if the socket will delay closing in an attempt to send all pending data. |
| [set_MulticastLoopback](./set_multicastloopback/)(bool) | Sets a value that indicates if the socket receives outgoing multicast packets. |
| [set_NoDelay](./set_nodelay/)(bool) | Sets a value that indicates if the socket is using the Nagle algorithm. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Sets the receive buffer size. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Sets a period after which a 'Receive' call will time out. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Sets the send buffer size. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Sets a period after which a 'Send' call will time out. |
| [set_Ttl](./set_ttl/)(int16_t) | Sets the TTL value. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Sets the specified socket option to the specified value. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Sets the specified socket option to the specified value. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, bool) | Sets the specified socket option to the specified value. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) | Sets the specified socket option to the specified value. |
| [Shutdown](./shutdown/)(SocketShutdown) | Disables the send and receive operations of the socket. |
| [Socket](./socket/)(System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Constructs a new instance. |
| [Socket](./socket/)(System::Net::Sockets::AddressFamily, System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Constructs a new instance. |
| virtual [~Socket](./~socket/)() | Destructs the current instance. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | The socket implementation. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
