---
title: "System::IO::Stream::BeginWrite‑metod"
linktitle: "BeginWrite"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream::BeginWrite‑metod. Initierar en asynkron skrivoperation i C++."
type: docs
weight: 200
url: /sv/cpp/system.io/stream/beginwrite/
---
## Stream::BeginWrite method


Initierar en asynkron skrivoperation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | En buffer som innehåller data som ska skrivas |
| förskjutning | int | En 0-baserad offset i **buffer** som indikerar positionen varifrån datan som ska skrivas börjar |
| count | int | Antalet byte att skriva |
| callback | System::AsyncCallback | Ett återanrop som ska anropas när operationen slutförs |
| state | System::SharedPtr\<System::Object\> | Användarlevererad data som används för att unikt identifiera varje asynkron skrivoperation |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona skrivoperationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
