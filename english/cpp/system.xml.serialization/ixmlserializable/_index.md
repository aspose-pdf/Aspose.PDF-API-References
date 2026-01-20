---
title: System::Xml::Serialization::IXmlSerializable class
linktitle: IXmlSerializable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Serialization::IXmlSerializable class. Provides custom formatting for XML serialization and deserialization. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


Provides custom formatting for XML serialization and deserialization. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetSchema](./getschema/)() | An XmlSchema object that describes the XML representation of the object that is returned by the [WriteXml()](./writexml/) method and accepted by the [ReadXml()](./readxml/) method. |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Deserializes object from its XML representation. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Serializes the current object to XML representation. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
