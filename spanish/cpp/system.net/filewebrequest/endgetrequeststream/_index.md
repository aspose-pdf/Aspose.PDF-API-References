---
title: "System::Net::FileWebRequest::EndGetRequestStream método"
linktitle: "EndGetRequestStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::FileWebRequest::EndGetRequestStream método. Espera hasta que la operación asíncrona especificada para obtener un flujo se complete en C++."
type: docs
weight: 500
url: /es/cpp/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream method


Espera hasta que la operación asíncrona especificada para obtener un flujo se complete.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
