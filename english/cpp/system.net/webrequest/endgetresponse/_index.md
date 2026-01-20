---
title: System::Net::WebRequest::EndGetResponse method
linktitle: EndGetResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::EndGetResponse method. Waits until the specified asynchronous request for the resource completes in C++.'
type: docs
weight: 1300
url: /cpp/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse method


Waits until the specified asynchronous request for the resource completes.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous request for the resource. |

### ReturnValue

The web response.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
