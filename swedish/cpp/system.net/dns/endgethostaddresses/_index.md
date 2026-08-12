---
title: "System::Net::Dns::EndGetHostAddresses metod"
linktitle: "EndGetHostAddresses"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Dns::EndGetHostAddresses metod. Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry‑class‑instans är klar i C++."
type: docs
weight: 500
url: /sv/cpp/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses method


Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron operation. |

### ReturnValue

En nyss skapad IPHostEntry-klassinstans.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
