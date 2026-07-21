---
title: "System::Net::Dns::EndResolve método"
linktitle: "EndResolve"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Dns::EndResolve método. Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-class se complete en C++."
type: docs
weight: 800
url: /es/cpp/system.net/dns/endresolve/
---
## Dns::EndResolve method


Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-class se complete.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asincrónica. |

### ReturnValue

Una instancia recién creada de la clase IPHostEntry.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
