---
title: System::Web::Services::Protocols namespace
linktitle: System::Web::Services::Protocols
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Web::Services::Protocols namespace in C++.'
type: docs
weight: 7800
url: /cpp/system.web.services.protocols/
---



## Classes

| Class | Description |
| --- | --- |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | This base class is used in all XML [Web](../system.web/) service client proxies that use HTTP. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | An instance of this class is passed as the argument on to the InvokeCompletedEventHandler delegate. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapClientMessage](./soapclientmessage/) | Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Specifies that all SOAP messages passed or returned from the method use the Document formatting. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Sets the default format for the SOAP requests and responses. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapHeader](./soapheader/) | Represents content of the SOAP header. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Specifies the SOAP header that the XML [Web](../system.web/) service method or the XML [Web](../system.web/) service client can process. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapHeaderCollection](./soapheadercollection/) | Contains a collection of instances of the [SoapHeader](./soapheader/) class. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | The client proxy services must inherit this class when the SOAP is used. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SoapMessage](./soapmessage/) | Represent the SOAP message. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [WebClientProtocol](./webclientprotocol/) | This base class is used in all XML [Web](../system.web/) service client proxies that were created using ASP.NET. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Enums

| Enum | Description |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Enumerates the SOAP header directions. |
| [SoapMessageStage](./soapmessagestage/) | Enumerates the processing stages of the SOAP messages. |
| [SoapParameterStyle](./soapparameterstyle/) | Enumerates the parameters formats in a SOAP message. |
| [SoapProtocolVersion](./soapprotocolversion/) | Enumerates the versions of SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Enumerates options of how a SOAP message is routed to the XML [Web](../system.web/) service. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SoapException](./soapexception/) |  |
