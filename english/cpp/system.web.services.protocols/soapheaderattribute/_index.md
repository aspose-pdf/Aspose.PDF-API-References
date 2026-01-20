---
title: System::Web::Services::Protocols::SoapHeaderAttribute class
linktitle: SoapHeaderAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapHeaderAttribute class. Specifies the SOAP header that the XML Web service method or the XML Web service client can process. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute class


Specifies the SOAP header that the XML [Web](../../system.web/) service method or the XML [Web](../../system.web/) service client can process. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## Methods

| Method | Description |
| --- | --- |
| [get_Direction](./get_direction/)() | RTTI information. |
| [get_MemberName](./get_membername/)() | Gets a member variable name of the XML SOAP service that is used to receive the SOAP header contents. |
| [get_Required](./get_required/)() | Gets a value that indicates if the SOAP header must be understood and processed by the recipient XML [Web](../../system.web/) service or XML [Web](../../system.web/) service client. |
| [set_Direction](./set_direction/)(SoapHeaderDirection) | Sets the SOAP header direction. |
| [set_MemberName](./set_membername/)(String) | Sets a member variable name of the XML SOAP service that is used to receive the SOAP header contents. |
| [set_Required](./set_required/)(bool) | Sets a value that indicates if the SOAP header must be understood and processed by the recipient XML [Web](../../system.web/) service or XML [Web](../../system.web/) service client. |
| [SoapHeaderAttribute](./soapheaderattribute/)(String) | Constructs a new instance. |
## See Also

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
