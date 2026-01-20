---
title: System::Net::Dns::EndGetHostByName method
linktitle: EndGetHostByName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::EndGetHostByName method. Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes in C++.'
type: docs
weight: 600
url: /cpp/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName method


Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation. |

### ReturnValue

A newly created IPHostEntry-class instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
