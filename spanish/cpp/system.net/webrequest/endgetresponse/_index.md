---
title: "System::Net::WebRequest::EndGetResponse método"
linktitle: "EndGetResponse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::WebRequest::EndGetResponse método. Espera hasta que la solicitud asíncrona especificada para el recurso se complete en C++."
type: docs
weight: 1300
url: /es/cpp/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse method


Espera hasta que la solicitud asíncrona especificada para el recurso se complete.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una solicitud asíncrona del recurso. |

### ReturnValue

La respuesta web.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
