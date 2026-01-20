---
title: System::Net::FileWebRequest::EndGetResponse method
linktitle: EndGetResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::FileWebRequest::EndGetResponse method. Waits until the specified asynchronous request for the resource completes in C++.'
type: docs
weight: 600
url: /cpp/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse method


Waits until the specified asynchronous request for the resource completes.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
