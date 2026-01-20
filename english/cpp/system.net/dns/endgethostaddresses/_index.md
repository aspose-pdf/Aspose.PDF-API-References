---
title: System::Net::Dns::EndGetHostAddresses method
linktitle: EndGetHostAddresses
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::EndGetHostAddresses method. Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes in C++.'
type: docs
weight: 500
url: /cpp/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses method


Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation. |

### ReturnValue

A newly created IPHostEntry-class instance.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
