---
title: System::Xml::Schema::XmlSchemaSimpleContentExtension class
linktitle: XmlSchemaSimpleContentExtension
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleContentExtension class. Represents the extension element for simple content from XML Schema as specified by the World Wide Web Consortium (W3C). This class can be used to derive simple types by extension. Such derivations are used to extend the simple type content of the element by adding attributes in C++.'
type: docs
weight: 6000
url: /cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Represents the **extension** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class can be used to derive simple types by extension. Such derivations are used to extend the simple type content of the element by adding attributes.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) to be used for the attribute value. |
| [get_Attributes](./get_attributes/)() | Returns the collection of [XmlSchemaAttribute](../xmlschemaattribute/) and [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Returns the name of a built-in data type or simple type from which this type is extended. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) to be used for the attribute value. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of a built-in data type or simple type from which this type is extended. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | Initializes a new instance of the [XmlSchemaSimpleContentExtension](./) class. |
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
