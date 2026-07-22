---
title: "System::Net::Dns::EndResolve-metod"
linktitle: "EndResolve"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Dns::EndResolve-metod. Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar i C++."
type: docs
weight: 800
url: /sv/cpp/system.net/dns/endresolve/
---
## Dns::EndResolve method


Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar en asynkron operation. |

### ReturnValue

En nyss skapad IPHostEntry-klassinstans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
