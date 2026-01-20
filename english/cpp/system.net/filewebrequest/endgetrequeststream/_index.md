---
title: System::Net::FileWebRequest::EndGetRequestStream method
linktitle: EndGetRequestStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::FileWebRequest::EndGetRequestStream method. Waits until the specified asynchronous operation to get a stream completes in C++.'
type: docs
weight: 500
url: /cpp/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream method


Waits until the specified asynchronous operation to get a stream completes.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
