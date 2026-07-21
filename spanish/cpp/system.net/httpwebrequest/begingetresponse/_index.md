---
title: "System::Net::HttpWebRequest::BeginGetResponse método"
linktitle: "BeginGetResponse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::HttpWebRequest::BeginGetResponse método. Inicia una solicitud asíncrona del recurso en C++."
type: docs
weight: 500
url: /es/cpp/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse method


Inicia una solicitud asíncrona para el recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
