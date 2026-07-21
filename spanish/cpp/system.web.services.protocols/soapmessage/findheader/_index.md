---
title: "System::Web::Services::Protocols::SoapMessage::FindHeader método"
linktitle: "FindHeader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::Services::Protocols::SoapMessage::FindHeader método. Encuentra el mapeo de encabezado por el tipo de encabezado especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader method


Encuentra el mapeo de la cabecera por el tipo de cabecera especificado.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headersInfo | System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\> | La colección de los mapeos de encabezados. |
| headerType | const TypeInfo\& | El tipo de encabezado a buscar. |

### ReturnValue

El mapeo de encabezado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.PDF for C++](../../../)
