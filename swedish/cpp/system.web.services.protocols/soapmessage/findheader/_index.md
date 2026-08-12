---
title: "System::Web::Services::Protocols::SoapMessage::FindHeader method"
linktitle: "FindHeader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapMessage::FindHeader method. Hitta rubrikmappningen med angiven rubriktyp i C++."
type: docs
weight: 300
url: /sv/cpp/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader method


Hitta huvudmappningen efter angiven huvudtyp.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headersInfo | System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\> | Samlingen av rubrikmappningarna. |
| headerType | const TypeInfo\& | Rubriktypen att leta efter. |

### ReturnValue

Rubrikmappningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.PDF for C++](../../../)
