---
title: System::Xml::Schema::IXmlSchemaInfo class
linktitle: IXmlSchemaInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::IXmlSchemaInfo class. Defines the post-schema-validation infoset of a validated XML node in C++.'
type: docs
weight: 100
url: /cpp/system.xml.schema/ixmlschemainfo/
---
## IXmlSchemaInfo class


Defines the post-schema-validation infoset of a validated XML node.

```cpp
class IXmlSchemaInfo : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_IsDefault](./get_isdefault/)() | Returns a value indicating if this validated XML node was set as the result of a default being applied during XML [Schema](../) Definition Language (XSD) schema validation. |
| virtual [get_IsNil](./get_isnil/)() | Returns a value indicating if the value for this validated XML node is **nil**. |
| virtual [get_MemberType](./get_membertype/)() | Returns the dynamic schema type for this validated XML node. |
| virtual [get_SchemaAttribute](./get_schemaattribute/)() | Returns the compiled [XmlSchemaAttribute](../xmlschemaattribute/) that corresponds to this validated XML node. |
| virtual [get_SchemaElement](./get_schemaelement/)() | Returns the compiled [XmlSchemaElement](../xmlschemaelement/) that corresponds to this validated XML node. |
| virtual [get_SchemaType](./get_schematype/)() | Returns the static XML [Schema](../) Definition Language (XSD) schema type of this validated XML node. |
| virtual [get_Validity](./get_validity/)() | Returns the [XmlSchemaValidity](../xmlschemavalidity/) value of this validated XML node. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
