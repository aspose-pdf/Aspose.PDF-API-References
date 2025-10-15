---
title: System::Xml::Schema::XmlSchemaInfo class
linktitle: XmlSchemaInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaInfo class. Represents the post-schema-validation infoset of a validated XML node in C++.'
type: docs
weight: 3800
url: /cpp/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo class


Represents the post-schema-validation infoset of a validated XML node.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Methods

| Method | Description |
| --- | --- |
| [get_ContentType](./get_contenttype/)() | Returns the [XmlSchemaContentType](../xmlschemacontenttype/) object that corresponds to the content type of this validated XML node. |
| [get_IsDefault](./get_isdefault/)() override | Returns a value indicating if this validated XML node was set as the result of a default being applied during XML [Schema](../) Definition Language (XSD) schema validation. |
| [get_IsNil](./get_isnil/)() override | Returns a value indicating if the value for this validated XML node is **nil**. |
| [get_MemberType](./get_membertype/)() override | Returns the dynamic schema type for this validated XML node. |
| [get_SchemaAttribute](./get_schemaattribute/)() override | Returns the compiled [XmlSchemaAttribute](../xmlschemaattribute/) object that corresponds to this validated XML node. |
| [get_SchemaElement](./get_schemaelement/)() override | Returns the compiled [XmlSchemaElement](../xmlschemaelement/) object that corresponds to this validated XML node. |
| [get_SchemaType](./get_schematype/)() override | Returns the static XML [Schema](../) Definition Language (XSD) schema type of this validated XML node. |
| [get_Validity](./get_validity/)() override | Returns the [XmlSchemaValidity](../xmlschemavalidity/) value of this validated XML node. |
| [set_ContentType](./set_contenttype/)(XmlSchemaContentType) | Sets the [XmlSchemaContentType](../xmlschemacontenttype/) object that corresponds to the content type of this validated XML node. |
| [set_IsDefault](./set_isdefault/)(bool) | Sets a value indicating if this validated XML node was set as the result of a default being applied during XML [Schema](../) Definition Language (XSD) schema validation. |
| [set_IsNil](./set_isnil/)(bool) | Sets a value indicating if the value for this validated XML node is **nil**. |
| [set_MemberType](./set_membertype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets the dynamic schema type for this validated XML node. |
| [set_SchemaAttribute](./set_schemaattribute/)(const SharedPtr\<XmlSchemaAttribute\>\&) | Sets the compiled [XmlSchemaAttribute](../xmlschemaattribute/) object that corresponds to this validated XML node. |
| [set_SchemaElement](./set_schemaelement/)(const SharedPtr\<XmlSchemaElement\>\&) | Sets the compiled [XmlSchemaElement](../xmlschemaelement/) object that corresponds to this validated XML node. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Sets the static XML [Schema](../) Definition Language (XSD) schema type of this validated XML node. |
| [set_Validity](./set_validity/)(XmlSchemaValidity) | Sets the [XmlSchemaValidity](../xmlschemavalidity/) value of this validated XML node. |
| [XmlSchemaInfo](./xmlschemainfo/)() | Initializes a new instance of the [XmlSchemaInfo](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IXmlSchemaInfo](../ixmlschemainfo/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
