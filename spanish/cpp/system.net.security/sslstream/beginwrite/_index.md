---
title: "System::Net::Security::SslStream::BeginWrite método"
linktitle: "BeginWrite"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::SslStream::BeginWrite método. Inicia una operación de escritura asíncrona en C++."
type: docs
weight: 400
url: /es/cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite method


Inicia una operación de escritura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | La matriz de bytes para escribir datos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| count | int32_t | El número de bytes a escribir. |
| asyncCallback | AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| asyncState | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de escritura asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de escritura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
