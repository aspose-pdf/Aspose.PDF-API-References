---
title: "System::Net::Sockets::NetworkStream::EndRead method"
linktitle: "EndRead"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::NetworkStream::EndRead method. Espera hasta que la operación de lectura asíncrona especificada se complete en C++."
type: docs
weight: 600
url: /es/cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead method


Espera hasta que la operación de lectura asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asíncrona. |

### ReturnValue

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
