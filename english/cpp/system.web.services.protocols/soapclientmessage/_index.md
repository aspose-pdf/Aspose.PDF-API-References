---
title: System::Web::Services::Protocols::SoapClientMessage class
linktitle: SoapClientMessage
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapClientMessage class. Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Methods

| Method | Description |
| --- | --- |
| [get_Action](./get_action/)() override | Returns a value of the 'SOAPAction' attribute. |
| [get_Client](./get_client/)() | Returns an instance of the client proxy class. |
| virtual [get_OneWay](./get_oneway/)() | Returns a value that indicates if a client doesn't wait for a server to finish processing a method. |
| [get_SoapVersion](./get_soapversion/)() override | Returns the SOAP version that is used. |
| [get_Url](./get_url/)() override | Returns the XML [Web](../../system.web/) service URL. |
| [SoapClientMessage](./soapclientmessage/)(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Constructs a new instance. |
## See Also

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
