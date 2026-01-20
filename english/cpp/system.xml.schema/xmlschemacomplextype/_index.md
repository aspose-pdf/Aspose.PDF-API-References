---
title: System::Xml::Schema::XmlSchemaComplexType class
linktitle: XmlSchemaComplexType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaComplexType class. Represents the complexType element from XML Schema as specified by the World Wide Web Consortium (W3C). This class defines a complex type that determines the set of attributes and content of an element in C++.'
type: docs
weight: 2100
url: /cpp/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType class


Represents the **complexType** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a complex type that determines the set of attributes and content of an element.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returns the value for the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex type. |
| [get_Attributes](./get_attributes/)() | Returns the collection of attributes for the complex type. |
| [get_AttributeUses](./get_attributeuses/)() | Returns the collection of all the complied attributes of this complex type and its base types. |
| [get_AttributeWildcard](./get_attributewildcard/)() | Returns the post-compilation value for **anyAttribute** for this complex type and its base type(s). |
| [get_Block](./get_block/)() | Returns the **block** attribute. |
| [get_BlockResolved](./get_blockresolved/)() | Returns the value after the type has been compiled to the post-schema-validation information set (infoset). This value indicates how the type is enforced when **xsi:type** is used in the instance document. |
| [get_ContentModel](./get_contentmodel/)() | Returns the post-compilation [XmlSchemaContentModel](../xmlschemacontentmodel/) of this complex type. |
| [get_ContentType](./get_contenttype/)() | Returns the content model of the complex type which holds the post-compilation value. |
| [get_ContentTypeParticle](./get_contenttypeparticle/)() | Returns the particle that holds the post-compilation value of the [XmlSchemaComplexType::get_ContentType](./get_contenttype/) particle. |
| [get_IsAbstract](./get_isabstract/)() | Returns the information that determines if the **complexType** element can be used in the instance document. |
| [get_IsMixed](./get_ismixed/)() override | Returns information that determines if the complex type has a mixed content model (markup within the content). |
| [get_Particle](./get_particle/)() | Returns the compositor type as one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Sets the value for the [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) component of the complex type. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Sets the **block** attribute. |
| [set_ContentModel](./set_contentmodel/)(const SharedPtr\<XmlSchemaContentModel\>\&) | Sets the post-compilation [XmlSchemaContentModel](../xmlschemacontentmodel/) of this complex type. |
| [set_IsAbstract](./set_isabstract/)(bool) | Sets the information that determines if the **complexType** element can be used in the instance document. |
| [set_IsMixed](./set_ismixed/)(bool) override | Sets information that determines if the complex type has a mixed content model (markup within the content). |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Sets the compositor type as one of the [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [XmlSchemaComplexType](./xmlschemacomplextype/)() | Initializes a new instance of the [XmlSchemaComplexType](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
