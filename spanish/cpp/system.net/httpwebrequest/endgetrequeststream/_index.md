---
title: "System::Net::HttpWebRequest::EndGetRequestStream method"
linktitle: "EndGetRequestStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::HttpWebRequest::EndGetRequestStream method. Espera hasta que la operación asíncrona especificada para obtener un flujo se complete en C++."
type: docs
weight: 600
url: /es/cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream method


Espera hasta que la operación asíncrona especificada para obtener un flujo se complete.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
