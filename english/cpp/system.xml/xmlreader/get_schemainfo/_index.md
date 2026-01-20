---
title: System::Xml::XmlReader::get_SchemaInfo method
linktitle: get_SchemaInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::get_SchemaInfo method. Returns the schema information that has been assigned to the current node as a result of schema validation in C++.'
type: docs
weight: 2200
url: /cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Returns the schema information that has been assigned to the current node as a result of schema validation.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

An IXmlSchemaInfo object containing the schema information for the current node. [Schema](../../../system.xml.schema/) information can be set on elements, attributes, or on text nodes with a non-null [XmlReader::get_ValueType](../get_valuetype/) value. If the current node is not one of the above node types, or if the [XmlReader](../) instance does not report schema information, this method returns **nullptr**. If this method is called from an [XmlTextReader](../../xmltextreader/) or an [XmlValidatingReader](../../xmlvalidatingreader/) object, this method always returns **nullptr**. These [XmlReader](../) implementations do not expose schema information through the get_SchemaInfo method.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
