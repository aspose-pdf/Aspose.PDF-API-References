---
title: System::Xml::Schema::XmlSchemaSimpleTypeUnion class
linktitle: XmlSchemaSimpleTypeUnion
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleTypeUnion class. Represents the union element for simple types from XML Schema as specified by the World Wide Web Consortium (W3C). A union datatype can be used to specify the content of a simpleType. The value of the simpleType element must be any one of a set of alternative datatypes specified in the union. Union types are always derived types and must comprise at least two alternative datatypes in C++.'
type: docs
weight: 6600
url: /cpp/system.xml.schema/xmlschemasimpletypeunion/
---
## XmlSchemaSimpleTypeUnion class


Represents the **union** element for simple types from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). A **union** datatype can be used to specify the content of a **simpleType**. The value of the **simpleType** element must be any one of a set of alternative datatypes specified in the union. Union types are always derived types and must comprise at least two alternative datatypes.

```cpp
class XmlSchemaSimpleTypeUnion : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaseMemberTypes](./get_basemembertypes/)() | Returns an array of [XmlSchemaSimpleType](../xmlschemasimpletype/) objects representing the type of the **simpleType** element based on the [XmlSchemaSimpleTypeUnion::get_BaseTypes](./get_basetypes/) and [XmlSchemaSimpleTypeUnion::get_MemberTypes](./get_membertypes/) values of the simple type. |
| [get_BaseTypes](./get_basetypes/)() | Returns the collection of base types. |
| [get_MemberTypes](./get_membertypes/)() | Returns the array of qualified member names of built-in data types or **simpleType** elements defined in this schema (or another schema indicated by the specified namespace). |
| [set_MemberTypes](./set_membertypes/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Sets the array of qualified member names of built-in data types or **simpleType** elements defined in this schema (or another schema indicated by the specified namespace). |
| [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/)() | Initializes a new instance of the [XmlSchemaSimpleTypeUnion](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
