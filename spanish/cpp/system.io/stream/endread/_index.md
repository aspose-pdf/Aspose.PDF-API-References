---
title: "System::IO::Stream::EndRead método"
linktitle: "EndRead"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::Stream::EndRead método. Espera hasta que la operación de lectura asincrónica especificada se complete en C++."
type: docs
weight: 600
url: /es/cpp/system.io/stream/endread/
---
## Stream::EndRead method


Espera hasta que la operación de lectura asíncrona especificada se complete.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<System::IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asíncrona. |

### ReturnValue

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
