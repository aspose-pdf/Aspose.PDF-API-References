---
title: System::IO::Stream::EndRead method
linktitle: EndRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream::EndRead method. Waits until the specified asynchronous read operation completes in C++.'
type: docs
weight: 600
url: /cpp/system.io/stream/endread/
---
## Stream::EndRead method


Waits until the specified asynchronous read operation completes.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<System::IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
