---
title: System::Net::WebRequest::BeginGetResponse method
linktitle: BeginGetResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::BeginGetResponse method. Initiates an asynchronous request for the resource in C++.'
type: docs
weight: 1100
url: /cpp/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse method


Initiates an asynchronous request for the resource.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
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
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
