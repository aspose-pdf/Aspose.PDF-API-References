---
title: "System::Net::HttpWebRequest::EndGetResponse‑metod"
linktitle: "EndGetResponse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::HttpWebRequest::EndGetResponse metod. Väntar tills den angivna asynkrona begäran för resursen slutförs i C++."
type: docs
weight: 700
url: /sv/cpp/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse method


Väntar tills den angivna asynkrona begäran för resursen är klar.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
