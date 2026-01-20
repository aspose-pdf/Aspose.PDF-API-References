---
title: System::Xml::Schema::XmlSchema class
linktitle: XmlSchema
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchema class. An in-memory representation of an XML Schema, as specified in the World Wide Web Consortium (W3C)  and  in C++.'
type: docs
weight: 400
url: /cpp/system.xml.schema/xmlschema/
---
## XmlSchema class


An in-memory representation of an XML [Schema](../), as specified in the World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) and [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [Compile](./compile/)(ValidationEventHandler) | Compiles the XML [Schema](../)[Object](../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation. |
| [Compile](./compile/)(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) | Compiles the XML [Schema](../)[Object](../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation. |
| [get_AttributeFormDefault](./get_attributeformdefault/)() | Returns the form for attributes declared in the target namespace of the schema. |
| [get_AttributeGroups](./get_attributegroups/)() | Returns the post-schema-compilation value of all the global attribute groups in the schema. |
| [get_Attributes](./get_attributes/)() | Returns the post-schema-compilation value for all the attributes in the schema. |
| [get_BlockDefault](./get_blockdefault/)() | Returns the **blockDefault** attribute which sets the default value of the **block** attribute on element and complex types in the **targetNamespace** of the schema. |
| [get_ElementFormDefault](./get_elementformdefault/)() | Returns the form for elements declared in the target namespace of the schema. |
| [get_Elements](./get_elements/)() | Returns the post-schema-compilation value for all the elements in the schema. |
| [get_FinalDefault](./get_finaldefault/)() | Returns the **finalDefault** attribute which sets the default value of the **final** attribute on elements and complex types in the target namespace of the schema. |
| [get_Groups](./get_groups/)() | Returns the post-schema-compilation value of all the groups in the schema. |
| [get_Id](./get_id/)() | Returns the string ID. |
| [get_Includes](./get_includes/)() | Returns the collection of included and imported schemas. |
| [get_IsCompiled](./get_iscompiled/)() | Indicates if the schema has been compiled. |
| [get_Items](./get_items/)() | Returns the collection of schema elements in the schema and is used to add new element types at the **schema** element level. |
| [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returns the line number in the file to which the **schema** element refers. |
| [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returns the line position in the file to which the **schema** element refers. |
| [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returns the XmlSerializerNamespaces to use with this schema object. |
| [get_Notations](./get_notations/)() | Returns the post-schema-compilation value for all notations in the schema. |
| [get_Parent](../xmlschemaobject/get_parent/)() | Returns the parent of this [XmlSchemaObject](../xmlschemaobject/). |
| [get_SchemaTypes](./get_schematypes/)() | Returns the post-schema-compilation value of all schema types in the schema. |
| [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returns the source location for the file that loaded the schema. |
| [get_TargetNamespace](./get_targetnamespace/)() | Returns the Uniform Resource Identifier (URI) of the schema target namespace. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returns the qualified attributes which do not belong to the schema target namespace. |
| [get_Version](./get_version/)() | Returns the version of the schema. |
| static [Read](./read/)(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) | Reads an XML [Schema](../) from the supplied [IO::TextReader](../../system.io/textreader/). |
| static [Read](./read/)(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) | Reads an XML [Schema](../) from the supplied stream. |
| static [Read](./read/)(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) | Reads an XML [Schema](../) from the supplied [XmlReader](../../system.xml/xmlreader/). |
| [set_AttributeFormDefault](./set_attributeformdefault/)(XmlSchemaForm) | Sets the form for attributes declared in the target namespace of the schema. |
| [set_BlockDefault](./set_blockdefault/)(XmlSchemaDerivationMethod) | Sets the **blockDefault** attribute which sets the default value of the **block** attribute on element and complex types in the **targetNamespace** of the schema. |
| [set_ElementFormDefault](./set_elementformdefault/)(XmlSchemaForm) | Sets the form for elements declared in the target namespace of the schema. |
| [set_FinalDefault](./set_finaldefault/)(XmlSchemaDerivationMethod) | Sets the **finalDefault** attribute which sets the default value of the **final** attribute on elements and complex types in the target namespace of the schema. |
| [set_Id](./set_id/)(const String\&) | Sets the string ID. |
| [set_LineNumber](../xmlschemaobject/set_linenumber/)(int32_t) | Sets the line number in the file to which the **schema** element refers. |
| [set_LinePosition](../xmlschemaobject/set_lineposition/)(int32_t) | Sets the line position in the file to which the **schema** element refers. |
| [set_Namespaces](../xmlschemaobject/set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Sets the XmlSerializerNamespaces to use with this schema object. |
| [set_Parent](../xmlschemaobject/set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Sets the parent of this [XmlSchemaObject](../xmlschemaobject/). |
| [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const String\&) | Sets the source location for the file that loaded the schema. |
| [set_TargetNamespace](./set_targetnamespace/)(const String\&) | Sets the Uniform Resource Identifier (URI) of the schema target namespace. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Sets the qualified attributes which do not belong to the schema target namespace. |
| [set_Version](./set_version/)(const String\&) | Sets the version of the schema. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&) | Writes the XML [Schema](../) to the supplied data stream. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Writes the XML [Schema](../) to the supplied Stream using the [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) specified. |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&) | Writes the XML [Schema](../) to the supplied [IO::TextWriter](../../system.io/textwriter/). |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Writes the XML [Schema](../) to the supplied TextWriter. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&) | Writes the XML [Schema](../) to the supplied [XmlWriter](../../system.xml/xmlwriter/). |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Writes the XML [Schema](../) to the supplied [XmlWriter](../../system.xml/xmlwriter/). |
| [XmlSchema](./xmlschema/)() | Initializes a new instance of the [XmlSchema](./) class. |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initializes a new instance of the [XmlSchemaObject](../xmlschemaobject/) class. |
## Fields

| Field | Description |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | The XML schema instance namespace. This field is constant. |
| static [Namespace](./namespace/) | The XML schema namespace. This field is constant. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
