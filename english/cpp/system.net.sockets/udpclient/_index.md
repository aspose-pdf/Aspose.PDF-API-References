---
title: System::Net::Sockets::UdpClient class
linktitle: UdpClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::UdpClient class. Provides User Datagram Protocol (UDP) network services. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.net.sockets/udpclient/
---
## UdpClient class


Provides User Datagram Protocol (UDP) network services. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UdpClient : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() | Closes the UDP connection. |
| [Connect](./connect/)(String, int32_t) | Establishes a connection to the specified port on the specified host. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establishes a connection with the host at the specified address on the specified port. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Establishes a connection to a remote end point. |
| [Dispose](./dispose/)() override | Releases the managed and unmanaged resources used by the [UdpClient](./). |
| [get_Client](./get_client/)() | RTTI information. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Returns a datagram sent by a server. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Sends a UDP datagram to the host at the remote end point. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Sends a UDP datagram to the specified port on the specified remote host. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Sends a UDP datagram to a remote host. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Used to provide the underlying network socket. |
| [UdpClient](./udpclient/)() | Initializes a new instance of the [UdpClient](./) class. |
| [UdpClient](./udpclient/)(AddressFamily) | Initializes a new instance of the [UdpClient](./) class. |
| [UdpClient](./udpclient/)(int32_t) | Initializes a new instance of the [UdpClient](./) class. |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | Initializes a new instance of the [UdpClient](./) class. |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | Initializes a new instance of the [UdpClient](./) class. param local EP the local endpoint to which you bind the UDP connection. |
| [UdpClient](./udpclient/)(String, int32_t) | Creates a new instance of the [UdpClient](./) class and connects to the specified remote host on the specified port. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
