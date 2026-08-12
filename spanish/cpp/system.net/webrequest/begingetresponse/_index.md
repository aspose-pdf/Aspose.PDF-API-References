---
title: "System::Net::WebRequest::BeginGetResponse método"
linktitle: "BeginGetResponse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::WebRequest::BeginGetResponse método. Inicia una solicitud asíncrona para el recurso en C++."
type: docs
weight: 1100
url: /es/cpp/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse method


Inicia una solicitud asíncrona para el recurso.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| state | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asincrónica. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asincrónica iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
