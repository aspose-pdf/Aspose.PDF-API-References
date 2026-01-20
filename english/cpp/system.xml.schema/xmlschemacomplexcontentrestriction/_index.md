---
title: System::Xml::Schema::XmlSchemaComplexContentRestriction class
linktitle: XmlSchemaComplexContentRestriction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaComplexContentRestriction class. Represents the restriction element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is for complex types with a complex content model derived by restriction. It restricts the contents of the complex type to a subset of the inherited complex type in C++.'
type: docs
weight: 2000
url: /cpp/system.xml.schema/xmlschemacomplexcontentrestriction/
---
## XmlSchemaComplexContentRestriction class


Represents the **restriction** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is for complex types with a complex content model derived by restriction. It restricts the contents of the complex type to a subset of the inherited complex type.

```cpp
class XmlSchemaComplexContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex content model. |
| [get_Attributes](./get_attributes/)() | Returns the collection of attributes for the complex type. Contains the [XmlSchemaAttribute](../xmlschemaattribute/) and [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) elements. |
| [get_BaseTypeName](./get_basetypename/)() | Returns the name of a complex type from which this type is derived by restriction. |
| [get_Particle](./get_particle/)() | Returns one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex content model. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of a complex type from which this type is derived by restriction. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Sets one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/)() | Initializes a new instance of the [XmlSchemaComplexContentRestriction](./) class. |
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
