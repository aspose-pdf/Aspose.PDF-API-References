---
title: System::Web::Services::Protocols::SoapMessage class
linktitle: SoapMessage
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::SoapMessage class. Represent the SOAP message. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.web.services.protocols/soapmessage/
---
## SoapMessage class


Represent the SOAP message. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapMessage : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CollectHeaders](./collectheaders/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) | Sets the internal collection of the SOAP headers. |
| [FindHeader](./findheader/)(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) | Find the header mapping by specified header type. |
| virtual [get_Action](./get_action/)() | Returns a value of the 'SOAPAction' attribute. |
| [get_ContentEncoding](./get_contentencoding/)() | Gets a value of the 'Content-Encoding' header. |
| [get_ContentType](./get_contenttype/)() | Gets a value of the 'Content-Type' header. |
| [get_Exception](./get_exception/)() | Gets the exception that is thrown by the XML [Web](../../system.web/) service method. |
| [get_Headers](./get_headers/)() | Returns the collection of the SOAP headers. |
| [get_InParameters](./get_inparameters/)() | Gets the parameters that are passed into the XML [Web](../../system.web/) service method. |
| [get_IsSoap12](./get_issoap12/)() | Returns a value that indicates if SOAP version 1.2 is used. |
| [get_OutParameters](./get_outparameters/)() | Gets the output parameters passed into the XML [Web](../../system.web/) service method. |
| virtual [get_SoapVersion](./get_soapversion/)() | Returns the SOAP version that is used. |
| [get_Stage](./get_stage/)() | Gets the processing stage of a SOAP message. |
| [get_Stream](./get_stream/)() | Gets the stream that contains the SOAP message data. |
| virtual [get_Url](./get_url/)() | Returns the XML [Web](../../system.web/) service URL. |
| [GetInParameterValue](./getinparametervalue/)(int32_t) | Gets the input parameter value at the specified index. |
| [GetOutParameterValue](./getoutparametervalue/)(int32_t) | Gets the output parameter value at the specified index. |
| [GetReturnValue](./getreturnvalue/)() | Gets the return value of the XML [Web](../../system.web/) service method. |
| [set_ContentEncoding](./set_contentencoding/)(String) | Sets a value of the 'Content-Encoding' header. |
| [set_ContentType](./set_contenttype/)(String) | Sets a value of the 'Content-Type' header. |
| [set_InParameters](./set_inparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Sets the parameters that are passed into the XML [Web](../../system.web/) service method. |
| [set_InternalStream](./set_internalstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the stream that contains the SOAP message data. |
| [set_OutParameters](./set_outparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Sets the output parameters passed into the XML [Web](../../system.web/) service method. |
| [SetException](./setexception/)(SoapException) | Sets the exception that is thrown by the XML [Web](../../system.web/) service method. |
| [SetHeaders](./setheaders/)(System::SharedPtr\<SoapHeaderCollection\>) | Sets the collection of the SOAP headers. |
| [SetStage](./setstage/)(SoapMessageStage) | Sets the processing stage of the SOAP message. |
| [SetStream](./setstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the stream that contains the SOAP message data. |
| [SoapMessage](./soapmessage/)() | Constructs a new instance. |
| [UpdateHeaderValues](./updateheadervalues/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>) | Updates the internal collection of the SOAP headers. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
