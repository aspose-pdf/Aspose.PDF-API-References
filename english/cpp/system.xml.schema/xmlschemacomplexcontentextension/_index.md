---
title: System::Xml::Schema::XmlSchemaComplexContentExtension class
linktitle: XmlSchemaComplexContentExtension
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaComplexContentExtension class. Represents the extension element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is for complex types with complex content model derived by extension. It extends the complex type by adding attributes or elements in C++.'
type: docs
weight: 1900
url: /cpp/system.xml.schema/xmlschemacomplexcontentextension/
---
## XmlSchemaComplexContentExtension class


Represents the **extension** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is for complex types with complex content model derived by extension. It extends the complex type by adding attributes or elements.

```cpp
class XmlSchemaComplexContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex content model. |
| [get_Attributes](./get_attributes/)() | Returns the collection of attributes for the complex content. Contains [XmlSchemaAttribute](../xmlschemaattribute/) and [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) elements. |
| [get_BaseTypeName](./get_basetypename/)() | Returns the name of the complex type from which this type is derived by extension. |
| [get_Particle](./get_particle/)() | Returns one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex content model. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the complex type from which this type is derived by extension. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Sets one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [XmlSchemaComplexContentExtension](./xmlschemacomplexcontentextension/)() | Initializes a new instance of the [XmlSchemaComplexContentExtension](./) class. |
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
