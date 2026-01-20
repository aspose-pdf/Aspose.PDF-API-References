---
title: System::Web::Services::Protocols::SoapParameterStyle enum
linktitle: SoapParameterStyle
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapParameterStyle enum. Enumerates the parameters formats in a SOAP message in C++.'
type: docs
weight: 1400
url: /cpp/system.web.services.protocols/soapparameterstyle/
---
## SoapParameterStyle enum


Enumerates the parameters formats in a SOAP message.

```cpp
enum class SoapParameterStyle
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | If '[SoapDocumentServiceAttribute](../soapdocumentserviceattribute/)' is not applied to the class, then the default value is 'Wrapped'. |
| Bare | 1 | The parameters are placed in XML elements that follow the 'Body' element. |
| Wrapped | 2 | The parameters are encapsulated within a single XML element that follows the 'Body' element. |

## See Also

* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
