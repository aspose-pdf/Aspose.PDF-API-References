---
title: System::Net::HttpWebRequest::BeginGetRequestStream method
linktitle: BeginGetRequestStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::HttpWebRequest::BeginGetRequestStream method. Initiates an asynchronous operation to get a stream for writing data to the resource in C++.'
type: docs
weight: 400
url: /cpp/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream method


Initiates an asynchronous operation to get a stream for writing data to the resource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | AsyncCallback | A callback to be called when the operation completes. |
| state | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
