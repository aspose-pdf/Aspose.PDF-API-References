---
title: "System::Net::Security::SslStream::BeginRead metod"
linktitle: "BeginRead"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::BeginRead metod. Initierar en asynkron läsoperation i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead method


Initierar en asynkron läsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen att läsa data från. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| count | int32_t | Antalet byte att läsa. |
| asyncCallback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| asyncState | System::SharedPtr\<Object\> | Användarlevererad data som används för att unikt identifiera varje asynkron läsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona läsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
