---
title: System::Net::ServicePoint class
linktitle: ServicePoint
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::ServicePoint class. Provides HTTP connection management. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3100
url: /cpp/system.net/servicepoint/
---
## ServicePoint class


Provides HTTP connection management. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ServicePoint : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CloseConnectionGroup](./closeconnectiongroup/)(String) | Closes and removes connections that belong to the specified connection group. |
| [get_Address](./get_address/)() | Returns the server URI to which the current instance connects. |
| [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | RTTI information. |
| [get_Certificate](./get_certificate/)() | Returns a certificate that is used by the current instance. |
| [get_ClientCertificate](./get_clientcertificate/)() | Returns the last client certificate. |
| [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Gets a timeout in milliseconds after which active [ServicePoint](./) will be closed. |
| [get_ConnectionLimit](./get_connectionlimit/)() | Gets the maximum number of connections that are allowed by the current instance. |
| [get_ConnectionName](./get_connectionname/)() | Returns the connection name. |
| [get_CurrentConnections](./get_currentconnections/)() | Returns a number of opened connections. |
| [get_Expect100Continue](./get_expect100continue/)() | Gets a value that indicates if the 100-Continue behavior is used. |
| [get_IdleSince](./get_idlesince/)() | Returns a date and time of the latest connection to a host. |
| [get_MaxIdleTime](./get_maxidletime/)() | Gets an amount of time in milliseconds after which an idle connection will be closed. |
| virtual [get_ProtocolVersion](./get_protocolversion/)() | Returns the HTTP version. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Gets the size of the receive buffer. |
| [get_SupportsPipelining](./get_supportspipelining/)() | Returns a value that indicates if the current instance supports the pipeline connections. |
| [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Gets a value that indicates if the Nagle algorithm is used by connections managed by the current instance. |
| [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)(BindIPEndPoint) | Sets the delegate that is used to associate local [IPEndPoint](../ipendpoint/) with the current instance. |
| [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(int32_t) | Sets a timeout in milliseconds after which active [ServicePoint](./) will be closed. |
| [set_ConnectionLimit](./set_connectionlimit/)(int32_t) | Sets the maximum number of connections that are allowed by the current instance. |
| [set_Expect100Continue](./set_expect100continue/)(bool) | Sets a value that indicates if the 100-Continue behavior is used. |
| [set_MaxIdleTime](./set_maxidletime/)(int32_t) | Sets an amount of time in milliseconds after which an idle connection will be closed. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Sets the size of the receive buffer. |
| [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Sets a value that indicates if the Nagle algorithm is used by connections managed by the current instance. |
| [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Sets the value that indicates if the 'Keep-Alive' option is enabled. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
