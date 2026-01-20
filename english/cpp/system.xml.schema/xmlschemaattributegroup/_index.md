---
title: System::Xml::Schema::XmlSchemaAttributeGroup class
linktitle: XmlSchemaAttributeGroup
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAttributeGroup class. Represents the attributeGroup element from the XML Schema as specified by the World Wide Web Consortium (W3C). AttributesGroups provides a mechanism to group a set of attribute declarations so that they can be incorporated as a group into complex type definitions in C++.'
type: docs
weight: 1200
url: /cpp/system.xml.schema/xmlschemaattributegroup/
---
## XmlSchemaAttributeGroup class


Represents the **attributeGroup** element from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). AttributesGroups provides a mechanism to group a set of attribute declarations so that they can be incorporated as a group into complex type definitions.

```cpp
class XmlSchemaAttributeGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the attribute group. |
| [get_Attributes](./get_attributes/)() | Returns the collection of attributes for the attribute group. Contains [XmlSchemaAttribute](../xmlschemaattribute/) and [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) elements. |
| [get_Name](./get_name/)() | Returns the name of the attribute group. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the qualified name of the attribute group. |
| [get_RedefinedAttributeGroup](./get_redefinedattributegroup/)() | Returns the redefined attribute group property from the XML [Schema](../). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the attribute group. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the attribute group. |
| [XmlSchemaAttributeGroup](./xmlschemaattributegroup/)() | Initializes a new instance of the [XmlSchemaAttributeGroup](./) class. |
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
