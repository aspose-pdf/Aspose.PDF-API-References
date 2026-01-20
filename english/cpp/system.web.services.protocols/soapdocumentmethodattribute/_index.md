---
title: System::Web::Services::Protocols::SoapDocumentMethodAttribute class
linktitle: SoapDocumentMethodAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapDocumentMethodAttribute class. Specifies that all SOAP messages passed or returned from the method use the Document formatting. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute class


Specifies that all SOAP messages passed or returned from the method use the Document formatting. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Methods

| Method | Description |
| --- | --- |
| [get_Action](./get_action/)() | RTTI information. |
| [get_Binding](./get_binding/)() | Gets the binding for which an XML web service method is implementing an operation. |
| [get_OneWay](./get_oneway/)() | Gets a value that indicates if a client doesn't wait for a server to finish processing a method. |
| [get_ParameterStyle](./get_parameterstyle/)() | Gets a value that indicates if parameters are encapsulated within a single XML element beneath the 'Body' element. |
| [get_RequestElementName](./get_requestelementname/)() | Gets the name of the XML element associated with the SOAP request, which is defined in a service description as an operation. |
| [get_RequestNamespace](./get_requestnamespace/)() | Gets the namespace associated with the SOAP request. |
| [get_ResponseElementName](./get_responseelementname/)() | Gets the name of the XML element associated with the SOAP response. |
| [get_ResponseNamespace](./get_responsenamespace/)() | Gets the namespace associated with the SOAP response. |
| [get_Use](./get_use/)() | Gets a value that determines the message encoding method. |
| [set_Action](./set_action/)(String) | Sets a value of the 'SOAPAction' attribute. |
| [set_Binding](./set_binding/)(String) | Sets the binding for which an XML web service method is implementing an operation. |
| [set_OneWay](./set_oneway/)(bool) | Sets a value that indicates if the client doesn't wait for the server to finish processing a method. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Sets a value that indicates if parameters are encapsulated within a single XML element beneath the 'Body' element. |
| [set_RequestElementName](./set_requestelementname/)(String) | Sets the name of the XML element associated with the SOAP request, which is defined in a service description as an operation. |
| [set_RequestNamespace](./set_requestnamespace/)(String) | Sets the namespace associated with the SOAP request. |
| [set_ResponseElementName](./set_responseelementname/)(String) | Sets the name of the XML element associated with the SOAP response. |
| [set_ResponseNamespace](./set_responsenamespace/)(String) | Sets the namespace associated with the SOAP response. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Sets a value that determines the message encoding method. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Constructs a new instance. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)(String) | Constructs a new instance. |
## See Also

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
