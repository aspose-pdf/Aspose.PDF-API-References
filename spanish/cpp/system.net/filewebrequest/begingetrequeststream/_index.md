---
title: "System::Net::FileWebRequest::BeginGetRequestStream método"
linktitle: "BeginGetRequestStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::FileWebRequest::BeginGetRequestStream método. Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso en C++."
type: docs
weight: 300
url: /es/cpp/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream method


Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
