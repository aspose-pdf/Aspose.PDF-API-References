---
title: System::Web::Services::Protocols::SoapHeader class
linktitle: SoapHeader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapHeader class. Represents content of the SOAP header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


Represents content of the SOAP header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapHeader : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Actor](./get_actor/)() | Gets the URI of the SOAP header recipient when SOAP version 1.1 is used. |
| [get_DidUnderstand](./get_didunderstand/)() | Gets a value that indicates if the SOAP header is properly processed. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Gets a value of the 'mustUnderstand' attribute when SOAP version 1.1 is used. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Gets a value of the 'mustUnderstand' attribute when SOAP version 1.2 is used. |
| [get_EncodedRelay](./get_encodedrelay/)() | Gets a string representation of the 'relay' attribute value. |
| [get_MustUnderstand](./get_mustunderstand/)() | Gets a value that indicates if the SOAP header must be understood. |
| [get_Relay](./get_relay/)() | Gets a value of the 'relay' attribute. |
| [get_Role](./get_role/)() | Gets the URI of the SOAP header recipient when SOAP version 1.2 is used. |
| [set_Actor](./set_actor/)(String) | Sets the URI of the SOAP header recipient when SOAP version 1.1 is used. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | Sets a value that indicates if the SOAP header is properly processed. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | Sets a value of the 'mustUnderstand' attribute when SOAP version 1.1 is used. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | Sets a value of the 'mustUnderstand' attribute when SOAP version 1.2 is used. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | Sets a string representation of the 'relay' attribute value. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | Sets a value that indicates if the SOAP header must be understood. |
| [set_Relay](./set_relay/)(bool) | Sets a value of the 'relay' attribute. |
| [set_Role](./set_role/)(String) | Sets the URI of the SOAP header recipient when SOAP version 1.2 is used. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Constructs a new instance. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
