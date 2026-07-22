---
title: "System::Net::Dns::BeginGetHostAddresses metod"
linktitle: "BeginGetHostAddresses"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Dns::BeginGetHostAddresses metod. Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress i C++."
type: docs
weight: 100
url: /sv/cpp/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses method


Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostNameOrAddress | String | En sträng som innehåller ett värdnamn eller en IP-adress. |
| requestCallback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användar‑tillhandahållen data som används för att unikt identifiera varje asynkron operation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
