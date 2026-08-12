---
title: "System::Net::Security::SslStream::EndRead metod"
linktitle: "EndRead"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::EndRead metod. Väntar tills den angivna asynkrona läsoperationen är klar i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.security/sslstream/endread/
---
## SslStream::EndRead method


Väntar tills den angivna asynkrona läsoperationen är klar.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron läsoperation |

### ReturnValue

Antalet byte som läses under läsoperationen som representeras av **asyncResult**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
