---
title: System::Xml::Schema::XmlSchemaSimpleContentRestriction class
linktitle: XmlSchemaSimpleContentRestriction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleContentRestriction class. Represents the restriction element for simple content from XML Schema as specified by the World Wide Web Consortium (W3C). This class can be used to derive simple types by restriction. Such derivations can be used to restrict the range of values for the element to a subset of the values specified in the inherited simple type in C++.'
type: docs
weight: 6100
url: /cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


Represents the **restriction** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class can be used to derive simple types by restriction. Such derivations can be used to restrict the range of values for the element to a subset of the values specified in the inherited simple type.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns an [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) to be used for the attribute value. |
| [get_Attributes](./get_attributes/)() | Returns the [XmlSchemaAttribute](../xmlschemaattribute/) and [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) collection of attributes for the simple type. |
| [get_BaseType](./get_basetype/)() | Returns the simple type base value. |
| [get_BaseTypeName](./get_basetypename/)() | Returns the name of the built-in data type or simple type from which this type is derived. |
| [get_Facets](./get_facets/)() | Returns an [Xml](../../system.xml/)[Schema](../) facet. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets an [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) to be used for the attribute value. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets the simple type base value. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the built-in data type or simple type from which this type is derived. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | Initializes a new instance of the [XmlSchemaSimpleContentRestriction](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
