---
title: "System::Net::WebRequest::EndGetRequestStream método"
linktitle: "EndGetRequestStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::WebRequest::EndGetRequestStream método. Espera hasta que la operación asíncrona especificada para obtener un flujo se complete en C++."
type: docs
weight: 1200
url: /es/cpp/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream method


Espera hasta que la operación asíncrona especificada para obtener un flujo se complete.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asíncrona para obtener un flujo. |

### ReturnValue

El flujo para escribir datos en el recurso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
