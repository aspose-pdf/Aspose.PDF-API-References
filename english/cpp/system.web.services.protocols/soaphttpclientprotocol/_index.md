---
title: System::Web::Services::Protocols::SoapHttpClientProtocol class
linktitle: SoapHttpClientProtocol
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapHttpClientProtocol class. The client proxy services must inherit this class when the SOAP is used. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol class


The client proxy services must inherit this class when the SOAP is used. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Methods

| Method | Description |
| --- | --- |
| [Discover](./discover/)() | Binds the current instance to the XML [Web](../../system.web/) service. |
| [get_SoapVersion](./get_soapversion/)() | Gets the SOAP version. |
| [InitializeSerializers](./initializeserializers/)(const System::TypeInfo\&, System::SharedPtr\<System::Xml::Serialization::XmlSerializerImplementation\>, String) | Initializes the internal fields. |
| [set_SoapVersion](./set_soapversion/)(SoapProtocolVersion) | Sets the SOAP version. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Constructs a new instance. |
## See Also

* Class [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
