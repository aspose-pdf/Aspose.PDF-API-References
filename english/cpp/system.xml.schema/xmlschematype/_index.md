---
title: System::Xml::Schema::XmlSchemaType class
linktitle: XmlSchemaType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaType class. The base class for all simple types and complex types in C++.'
type: docs
weight: 6800
url: /cpp/system.xml.schema/xmlschematype/
---
## XmlSchemaType class


The base class for all simple types and complex types.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaseSchemaType](./get_baseschematype/)() | Returns the post-compilation object type or the built-in XML [Schema](../) Definition Language (XSD) data type, simpleType element, or complexType element. This is a post-schema-compilation infoset value. |
| [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Returns the post-compilation value for the base type of this schema type. |
| [get_Datatype](./get_datatype/)() | Returns the post-compilation value for the data type of the complex type. |
| [get_DerivedBy](./get_derivedby/)() | Returns the post-compilation information on how this element was derived from its base type. |
| [get_Final](./get_final/)() | Returns the final attribute of the type derivation that indicates if further derivations are allowed. |
| [get_FinalResolved](./get_finalresolved/)() | Returns the post-compilation interpretation of the [XmlSchemaType::get_Final](./get_final/) value. |
| virtual [get_IsMixed](./get_ismixed/)() | Returns a value indicating if this type has a mixed content model. This call is only valid in a complex type. |
| [get_Name](./get_name/)() | Returns the name of the type. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the qualified name for the type built from the **Name** attribute of this type. This is a post-schema-compilation value. |
| [get_TypeCode](./get_typecode/)() | Returns the [XmlTypeCode](../xmltypecode/) of the type. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(XmlTypeCode) | Returns an [XmlSchemaComplexType](../xmlschemacomplextype/) that represents the built-in complex type of the complex type specified. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(const SharedPtr\<XmlQualifiedName\>\&) | Returns an [XmlSchemaComplexType](../xmlschemacomplextype/) that represents the built-in complex type of the complex type specified by qualified name. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const SharedPtr\<XmlQualifiedName\>\&) | Returns an [XmlSchemaSimpleType](../xmlschemasimpletype/) that represents the built-in simple type of the simple type that is specified by the qualified name. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(XmlTypeCode) | Returns an [XmlSchemaSimpleType](../xmlschemasimpletype/) that represents the built-in simple type of the specified simple type. |
| static [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) | Returns a value indicating if the derived schema type specified is derived from the base schema type specified. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Sets the final attribute of the type derivation that indicates if further derivations are allowed. |
| virtual [set_IsMixed](./set_ismixed/)(bool) | Sets a value indicating if this type has a mixed content model. This call is only valid in a complex type. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the type. |
| [XmlSchemaType](./xmlschematype/)() | Initializes a new instance of the [XmlSchemaType](./) class. |
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
