---
title: "System::Net::WebRequest::EndGetResponse metod"
linktitle: "EndGetResponse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest::EndGetResponse metod. Väntar tills den angivna asynkrona begäran om resursen slutförs i C++."
type: docs
weight: 1300
url: /sv/cpp/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse method


Väntar tills den angivna asynkrona begäran för resursen är klar.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
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
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
