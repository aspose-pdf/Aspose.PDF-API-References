---
title: "System::IO::Stream::EndRead metod"
linktitle: "EndRead"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream::EndRead metod. Väntar tills den angivna asynkrona läsoperationen är klar i C++."
type: docs
weight: 600
url: /sv/cpp/system.io/stream/endread/
---
## Stream::EndRead method


Väntar tills den angivna asynkrona läsoperationen är klar.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<System::IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron läsoperation |

### ReturnValue

Antalet byte som läses under läsoperationen som representeras av **asyncResult**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
