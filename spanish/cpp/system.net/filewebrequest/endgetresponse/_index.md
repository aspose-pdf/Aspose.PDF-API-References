---
title: "System::Net::FileWebRequest::EndGetResponse método"
linktitle: "EndGetResponse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::FileWebRequest::EndGetResponse método. Espera hasta que la solicitud asíncrona especificada para el recurso se complete en C++."
type: docs
weight: 600
url: /es/cpp/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse method


Espera hasta que la solicitud asíncrona especificada para el recurso se complete.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
