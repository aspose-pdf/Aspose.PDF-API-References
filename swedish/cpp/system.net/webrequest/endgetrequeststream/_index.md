---
title: "System::Net::WebRequest::EndGetRequestStream metod"
linktitle: "EndGetRequestStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest::EndGetRequestStream metod. Väntar tills den angivna asynkrona operationen för att hämta en ström är klar i C++."
type: docs
weight: 1200
url: /sv/cpp/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream method


Väntar tills den angivna asynkrona operationen för att hämta en ström är klar.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron operation för att hämta en ström. |

### ReturnValue

Strömmen för att skriva data till resursen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
