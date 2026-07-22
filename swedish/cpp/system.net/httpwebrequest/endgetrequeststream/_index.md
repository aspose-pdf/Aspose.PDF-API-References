---
title: "System::Net::HttpWebRequest::EndGetRequestStream metod"
linktitle: "EndGetRequestStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::HttpWebRequest::EndGetRequestStream metod. Väntar tills den angivna asynkrona operationen för att hämta en ström är klar i C++."
type: docs
weight: 600
url: /sv/cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream method


Väntar tills den angivna asynkrona operationen för att hämta en ström är klar.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
