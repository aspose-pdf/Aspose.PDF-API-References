---
title: System::Net::Sockets::TcpClient class
linktitle: TcpClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::TcpClient class. Represents a client for the TCP network services. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.net.sockets/tcpclient/
---
## TcpClient class


Represents a client for the TCP network services. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TcpClient : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous connect operation. |
| [Close](./close/)() | Closes the connection and disposes the current instance. |
| [Connect](./connect/)(String, int32_t) | Establishes a connection to the specified remote host. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establishes a connection to the specified remote host. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Establishes a connection to the specified remote host. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Establishes a connection to the specified remote host. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous connect operation completes. |
| [get_Available](./get_available/)() | Returns the number of bytes that are received and ready to read. |
| [get_Client](./get_client/)() | RTTI information. |
| [get_Connected](./get_connected/)() | Returns a value that indicates if the socket is connected to the remote host. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Gets a value that indicates if the current instance allows only one client to use a port. |
| [get_LingerState](./get_lingerstate/)() | Gets a value that indicates if the socket will delay closing in an attempt to send all pending data. |
| [get_NoDelay](./get_nodelay/)() | Gets a value that indicates if the current instance is using the Nagle algorithm. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Gets the size of the buffer that is used for receiving data. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Gets a value that indicates an amount of time after which data receiving will time out. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Gets the size of the buffer that is used for sending data. |
| [get_SendTimeout](./get_sendtimeout/)() | Gets a value that indicates an amount of time after which data sending will time out. |
| [GetStream](./getstream/)() | Returns the stream that is used for sending and receiving data. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Sets the socket. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Sets a value that indicates if the current instance allows only one client to use a port. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Sets a value that indicates if the socket will delay closing in an attempt to send all pending data. |
| [set_NoDelay](./set_nodelay/)(bool) | Sets a value that indicates if the current instance is using the Nagle algorithm. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Sets the size of the buffer that is used for receiving data. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Sets a value that indicates an amount of time after which data receiving will time out. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Sets the size of the buffer that is used for sending data. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Sets a value that indicates an amount of time after which data sending will time out. |
| [TcpClient](./tcpclient/)(System::SharedPtr\<IPEndPoint\>) | Constructs a new instance. |
| [TcpClient](./tcpclient/)() | Constructs a new instance. |
| [TcpClient](./tcpclient/)(AddressFamily) | Constructs a new instance. |
| [TcpClient](./tcpclient/)(String, int32_t) | Constructs a new instance. |
| virtual [~TcpClient](./~tcpclient/)() | Destructs the current instance. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
