---
title: "System::Net::HttpWebRequest::BeginGetRequestStream método"
linktitle: "BeginGetRequestStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::HttpWebRequest::BeginGetRequestStream método. Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso en C++."
type: docs
weight: 400
url: /es/cpp/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream method


Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
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
