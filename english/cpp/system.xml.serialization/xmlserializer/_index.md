---
title: System::Xml::Serialization::XmlSerializer class
linktitle: XmlSerializer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Serialization::XmlSerializer class. Performs serialization and deserialization of objects into and from XML documents. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Performs serialization and deserialization of objects into and from XML documents. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class XmlSerializer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Checks if specific reader is in deserializable state. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | Deserializes XML document into object. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | Deserializes XML document into object. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | Deserializes XML document into object. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | Deserializes XML document into object. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Serializes document into XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Serializes document into XML. |
## Fields

| Field | Description |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Encoding namespace name. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | WSDL types namespace name. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
