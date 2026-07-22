---
title: "System::Net::Security::SslStream::BeginWrite method"
linktitle: "BeginWrite"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::BeginWrite method. Initierar en asynkron skrivoperation i C++."
type: docs
weight: 400
url: /sv/cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite method


Initierar en asynkron skrivoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Bytearrayen att skriva data till. |
| förskjutning | int32_t | Offseten i byte i den angivna arrayen. |
| count | int32_t | Antalet byte som ska skrivas. |
| asyncCallback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| asyncState | System::SharedPtr\<Object\> | Användarlevererad data som används för att unikt identifiera varje asynkron skrivoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar den initierade asynkrona skrivoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
