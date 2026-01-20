---
title: System::Net::WebRequest::EndGetRequestStream method
linktitle: EndGetRequestStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::EndGetRequestStream method. Waits until the specified asynchronous operation to get a stream completes in C++.'
type: docs
weight: 1200
url: /cpp/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream method


Waits until the specified asynchronous operation to get a stream completes.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation to get a stream. |

### ReturnValue

The stream for writing data to the resource.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
