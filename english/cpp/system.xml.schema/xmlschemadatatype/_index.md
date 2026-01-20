---
title: System::Xml::Schema::XmlSchemaDatatype class
linktitle: XmlSchemaDatatype
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaDatatype class. The XmlSchemaDatatype class is an abstract class for mapping XML Schema definition language (XSD) types to runtime types in C++.'
type: docs
weight: 2400
url: /cpp/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype class


The [XmlSchemaDatatype](./) class is an abstract class for mapping XML [Schema](../) definition language (XSD) types to runtime types.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&) | Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](./), to the run-time type specified. |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](./), to the run-time type specified using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) if the [XmlSchemaDatatype](./) represents the **xs:QName** type or a type derived from it. |
| virtual [get_TokenizedType](./get_tokenizedtype/)() | When overridden in a derived class, gets the type for the **string** as specified in the World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0 specification. |
| virtual [get_TypeCode](./get_typecode/)() | Returns the [XmlTypeCode](../xmltypecode/) value for the simple type. |
| virtual [get_ValueType](./get_valuetype/)() | When overridden in a derived class, gets the type of the item. |
| virtual [get_Variety](./get_variety/)() | Returns the [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) value for the simple type. |
| virtual [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaDatatype\>) | This method always returns **false**. |
| virtual [ParseValue](./parsevalue/)(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) | When overridden in a derived class, validates the **string** specified against a built-in or user-defined simple type. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
