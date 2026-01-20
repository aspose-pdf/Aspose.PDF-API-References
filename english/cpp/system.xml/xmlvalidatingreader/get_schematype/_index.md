---
title: System::Xml::XmlValidatingReader::get_SchemaType method
linktitle: get_SchemaType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader::get_SchemaType method. Returns a schema type object in C++.'
type: docs
weight: 2700
url: /cpp/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType method


Returns a schema type object.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### ReturnValue

XmlSchemaDatatype, XmlSchemaSimpleType, or XmlSchemaComplexType depending whether the node value is a built in XML [Schema](../../../system.xml.schema/) definition language (XSD) type or a user defined simpleType or complexType; **nullptr** if the current node has no schema type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
