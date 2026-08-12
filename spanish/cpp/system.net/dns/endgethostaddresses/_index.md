---
title: "System::Net::Dns::EndGetHostAddresses método"
linktitle: "EndGetHostAddresses"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Dns::EndGetHostAddresses método. Espera hasta que la operación asincrónica especificada para crear una nueva instancia de la clase IPHostEntry se complete en C++."
type: docs
weight: 500
url: /es/cpp/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses method


Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-class se complete.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asincrónica. |

### ReturnValue

Una instancia recién creada de la clase IPHostEntry.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
