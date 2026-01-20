---
title: System::Net::Sockets::NetworkStream::EndRead method
linktitle: EndRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::NetworkStream::EndRead method. Waits until the specified asynchronous read operation completes in C++.'
type: docs
weight: 600
url: /cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead method


Waits until the specified asynchronous read operation completes.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
