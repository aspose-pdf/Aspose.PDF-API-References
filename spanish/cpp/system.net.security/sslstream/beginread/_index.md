---
title: "Método System::Net::Security::SslStream::BeginRead"
linktitle: "BeginRead"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Net::Security::SslStream::BeginRead. Inicia una operación de lectura asíncrona en C++."
type: docs
weight: 300
url: /es/cpp/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead method


Inicia una operación de lectura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | La matriz de bytes de la que leer los datos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| count | int32_t | El número de bytes a leer. |
| asyncCallback | AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| asyncState | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de lectura asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de lectura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
