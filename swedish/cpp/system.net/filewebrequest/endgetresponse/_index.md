---
title: "System::Net::FileWebRequest::EndGetResponse metod"
linktitle: "EndGetResponse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::FileWebRequest::EndGetResponse metod. Väntar tills den angivna asynkrona begäran om resursen slutförs i C++."
type: docs
weight: 600
url: /sv/cpp/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse method


Väntar tills den angivna asynkrona begäran för resursen är klar.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron begäran för resursen. |

### ReturnValue

Webbresponsen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
