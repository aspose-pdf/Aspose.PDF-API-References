---
title: "System::Net::Sockets::NetworkStream::EndRead metod"
linktitle: "EndRead"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::NetworkStream::EndRead metod. Väntar tills den angivna asynkrona läsoperationen är klar i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead method


Väntar tills den angivna asynkrona läsoperationen är klar.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron läsoperation |

### ReturnValue

Antalet byte som läses under läsoperationen som representeras av **asyncResult**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
