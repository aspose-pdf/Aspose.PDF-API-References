---
title: "System::Net::Dns::BeginGetHostEntry-metod"
linktitle: "BeginGetHostEntry"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Dns::BeginGetHostEntry-metod. Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress i C++."
type: docs
weight: 300
url: /sv/cpp/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostNameOrAddress | String | Strängen som innehåller ett värdnamn eller en IP‑adress. |
| requestCallback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| stateObject | System::SharedPtr\<Object\> | Användar‑tillhandahållen data som används för att unikt identifiera varje asynkron operation. |

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
## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna IP-adressen.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | System::SharedPtr\<IPAddress\> | IP-adressen. |
| requestCallback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| stateObject | System::SharedPtr\<Object\> | Användar‑tillhandahållen data som används för att unikt identifiera varje asynkron operation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
