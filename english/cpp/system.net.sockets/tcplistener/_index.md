---
title: System::Net::Sockets::TcpListener class
linktitle: TcpListener
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::TcpListener class. Represents a listener for the TCP network services. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.net.sockets/tcplistener/
---
## TcpListener class


Represents a listener for the TCP network services. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TcpListener : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AcceptSocket](./acceptsocket/)() | Accepts the pending connection request and returns the socket that is used to send and receive data. |
| [AcceptTcpClient](./accepttcpclient/)() | Accepts the pending connection request and returns the TcpClient-class instance that is used for sending and receiving data. |
| [AllowNatTraversal](./allownattraversal/)(bool) | Enables or disables the NAT traversal. |
| [BeginAcceptSocket](./beginacceptsocket/)(AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous accept operation. |
| [BeginAcceptTcpClient](./beginaccepttcpclient/)(AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous accept operation. |
| static [Create](./create/)(int32_t) | Creates a new instance using the specified port number. |
| [EndAcceptSocket](./endacceptsocket/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous accept operation completes. |
| [EndAcceptTcpClient](./endaccepttcpclient/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous accept operation completes. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Gets a value that indicates if the current instance allows only one client to use a port. |
| [get_LocalEndpoint](./get_localendpoint/)() | Returns the underlying endpoint. |
| [get_Server](./get_server/)() | RTTI information. |
| [Pending](./pending/)() | Returns a value that indicates if there are pending connection requests. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Sets a value that indicates if the current instance allows only one client to use a port. |
| [Start](./start/)() | Starts listening for the incoming connections. |
| [Start](./start/)(int32_t) | Starts listening for the incoming connections. |
| [Stop](./stop/)() | Stops listening for the incoming connections. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPEndPoint\>) | Constructs a new instance. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPAddress\>, int32_t) | Constructs a new instance. |
| [TcpListener](./tcplistener/)(int32_t) | Constructs a new instance. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
