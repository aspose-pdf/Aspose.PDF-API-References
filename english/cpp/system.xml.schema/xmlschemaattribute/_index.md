---
title: System::Xml::Schema::XmlSchemaAttribute class
linktitle: XmlSchemaAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAttribute class. Represents the attribute element from the XML Schema as specified by the World Wide Web Consortium (W3C). Attributes provide additional information for other document elements. The attribute tag is nested between the tags of a document''s element for the schema. The XML document displays attributes as named items in the opening tag of an element in C++.'
type: docs
weight: 1100
url: /cpp/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute class


Represents the **attribute** element from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). Attributes provide additional information for other document elements. The attribute tag is nested between the tags of a document's element for the schema. The XML document displays attributes as named items in the opening tag of an element.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_AttributeSchemaType](./get_attributeschematype/)() | Returns an [XmlSchemaSimpleType](../xmlschemasimpletype/) object representing the type of the attribute based on the [XmlSchemaAttribute::get_SchemaType](./get_schematype/) or [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) value of the attribute. |
| [get_AttributeType](./get_attributetype/)() | Returns the object based on the [XmlSchemaAttribute::get_SchemaType](./get_schematype/) or [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) value of the attribute that holds the post-compilation interpretation of the **AttributeType** value. |
| [get_DefaultValue](./get_defaultvalue/)() | Returns the default value for the attribute. |
| [get_FixedValue](./get_fixedvalue/)() | Returns the fixed value for the attribute. |
| [get_Form](./get_form/)() | Returns the form for the attribute. |
| [get_Name](./get_name/)() | Returns the name of the attribute. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the qualified name for the attribute. |
| [get_RefName](./get_refname/)() | Returns the name of an attribute declared in this schema (or another schema indicated by the specified namespace). |
| [get_SchemaType](./get_schematype/)() | Returns the attribute type to a simple type. |
| [get_SchemaTypeName](./get_schematypename/)() | Returns the name of the simple type defined in this schema (or another schema indicated by the specified namespace). |
| [get_Use](./get_use/)() | Returns information about how the attribute is used. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Sets the default value for the attribute. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Sets the fixed value for the attribute. |
| [set_Form](./set_form/)(XmlSchemaForm) | Sets the form for the attribute. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the attribute. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of an attribute declared in this schema (or another schema indicated by the specified namespace). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets the attribute type to a simple type. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the simple type defined in this schema (or another schema indicated by the specified namespace). |
| [set_Use](./set_use/)(XmlSchemaUse) | Sets information about how the attribute is used. |
| [XmlSchemaAttribute](./xmlschemaattribute/)() | Initializes a new instance of the [XmlSchemaAttribute](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
