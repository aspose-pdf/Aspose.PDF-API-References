---
title: System::Xml::Schema::XmlSchemaElement class
linktitle: XmlSchemaElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaElement class. Represents the element element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is the base class for all particle types and is used to describe an element in an XML document in C++.'
type: docs
weight: 2600
url: /cpp/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement class


Represents the **element** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is the base class for all particle types and is used to describe an element in an XML document.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Methods

| Method | Description |
| --- | --- |
| [get_Block](./get_block/)() | Returns a **Block** derivation. |
| [get_BlockResolved](./get_blockresolved/)() | Returns the post-compilation interpretation of the **Block** value. |
| [get_Constraints](./get_constraints/)() | Returns the collection of constraints on the element. |
| [get_DefaultValue](./get_defaultvalue/)() | Returns the default value of the element if its content is a simple type or content of the element is **textOnly**. |
| [get_ElementSchemaType](./get_elementschematype/)() | Returns an [XmlSchemaType](../xmlschematype/) object representing the type of the element based on the [XmlSchemaElement::get_SchemaType](./get_schematype/) or [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) values of the element. |
| [get_ElementType](./get_elementtype/)() | Returns an object based on the [XmlSchemaElement](./) or [XmlSchemaElement](./) of the element, which holds the post-compilation interpretation of the **ElementType** value. |
| [get_Final](./get_final/)() | Returns the **Final** value to indicate that no further derivations are allowed. |
| [get_FinalResolved](./get_finalresolved/)() | Returns the post-compilation interpretation of the **Final** value. |
| [get_FixedValue](./get_fixedvalue/)() | Returns the fixed value. |
| [get_Form](./get_form/)() | Returns the form for the element. |
| [get_IsAbstract](./get_isabstract/)() | Returns information to indicate if the element can be used in an instance document. |
| [get_IsNillable](./get_isnillable/)() | Returns information that indicates if **xsi:nil** can occur in the instance data. Indicates if an explicit nil value can be assigned to the element. |
| [get_Name](./get_name/)() | Returns the name of the element. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the actual qualified name for the given element. |
| [get_RefName](./get_refname/)() | Returns the reference name of an element declared in this schema (or another schema indicated by the specified namespace). |
| [get_SchemaType](./get_schematype/)() | Returns the type of the element. This can either be a complex type or a simple type. |
| [get_SchemaTypeName](./get_schematypename/)() | Returns the name of a built-in data type defined in this schema or another schema indicated by the specified namespace. |
| [get_SubstitutionGroup](./get_substitutiongroup/)() | Returns the name of an element that is being substituted by this element. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Sets a **Block** derivation. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Sets the default value of the element if its content is a simple type or content of the element is **textOnly**. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Sets the **Final** value to indicate that no further derivations are allowed. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Sets the fixed value. |
| [set_Form](./set_form/)(XmlSchemaForm) | Sets the form for the element. |
| [set_IsAbstract](./set_isabstract/)(bool) | Sets information to indicate if the element can be used in an instance document. |
| [set_IsNillable](./set_isnillable/)(bool) | Sets information that indicates if **xsi:nil** can occur in the instance data. Indicates if an explicit nil value can be assigned to the element. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the element. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the reference name of an element declared in this schema (or another schema indicated by the specified namespace). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Sets the type of the element. This can either be a complex type or a simple type. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of a built-in data type defined in this schema or another schema indicated by the specified namespace. |
| [set_SubstitutionGroup](./set_substitutiongroup/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of an element that is being substituted by this element. |
| [XmlSchemaElement](./xmlschemaelement/)() | Initializes a new instance of the [XmlSchemaElement](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
