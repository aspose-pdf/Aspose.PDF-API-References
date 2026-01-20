---
title: System::Web::Services::Protocols::SoapDocumentServiceAttribute class
linktitle: SoapDocumentServiceAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapDocumentServiceAttribute class. Sets the default format for the SOAP requests and responses. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute class


Sets the default format for the SOAP requests and responses. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Methods

| Method | Description |
| --- | --- |
| [get_ParameterStyle](./get_parameterstyle/)() | RTTI information. |
| [get_RoutingStyle](./get_routingstyle/)() | Gets a value that shows how the SOAP messages are routed to the service. |
| [get_Use](./get_use/)() | Gets the parameter formatting. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Sets a value that indicates if parameters are encapsulated within a single XML element beneath the 'Body' element. |
| [set_RoutingStyle](./set_routingstyle/)(SoapServiceRoutingStyle) | Sets a value that shows how the SOAP messages are routed to the service. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Sets the parameter formatting. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Constructs a new instance. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse) | Constructs a new instance. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse, SoapParameterStyle) | Constructs a new instance. |
## See Also

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
