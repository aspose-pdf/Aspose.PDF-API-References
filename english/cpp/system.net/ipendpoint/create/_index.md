---
title: System::Net::IPEndPoint::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IPEndPoint::Create method. Create a new instance of the EndPoint class using the specified socket address in C++.'
type: docs
weight: 200
url: /cpp/system.net/ipendpoint/create/
---
## IPEndPoint::Create method


Create a new instance of the [EndPoint](../../endpoint/) class using the specified socket address.

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| socketAddress | System::SharedPtr\<SocketAddress\> | The socket address that will be used to initialize a new instance. |

### ReturnValue

A newly created EndPoint-class instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../endpoint/)
* Class [SocketAddress](../../socketaddress/)
* Class [IPEndPoint](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
