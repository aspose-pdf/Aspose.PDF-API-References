---
title: "Método System::Net::Security::SslStream::EndRead"
linktitle: "EndRead"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Net::Security::SslStream::EndRead. Espera hasta que la operación de lectura asíncrona especificada se complete en C++."
type: docs
weight: 700
url: /es/cpp/system.net.security/sslstream/endread/
---
## SslStream::EndRead method


Espera hasta que la operación de lectura asíncrona especificada se complete.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asíncrona. |

### ReturnValue

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
