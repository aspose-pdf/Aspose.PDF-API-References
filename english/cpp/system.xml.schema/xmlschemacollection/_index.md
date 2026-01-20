---
title: System::Xml::Schema::XmlSchemaCollection class
linktitle: XmlSchemaCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaCollection class. Contains a cache of XML Schema definition language (XSD) and XML-Data Reduced (XDR) schemas in C++.'
type: docs
weight: 1500
url: /cpp/system.xml.schema/xmlschemacollection/
---
## XmlSchemaCollection class


Contains a cache of XML [Schema](../) definition language (XSD) and XML-Data Reduced (XDR) schemas.

```cpp
class XmlSchemaCollection : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Adds the schema located by the given URL into the schema collection. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&) | Adds the schema contained in the [XmlReader](../../system.xml/xmlreader/) to the schema collection. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Adds the schema contained in the [XmlReader](../../system.xml/xmlreader/) to the schema collection. The specified [XmlResolver](../../system.xml/xmlresolver/) is used to resolve any external resources. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Adds the [XmlSchema](../xmlschema/) to the collection. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Adds the [XmlSchema](../xmlschema/) to the collection. The specified [XmlResolver](../../system.xml/xmlresolver/) is used to resolve any external references. |
| [Add](./add/)(const SharedPtr\<XmlSchemaCollection\>\&) | Adds all the namespaces defined in the given collection (including their associated schemas) to this collection. |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Returns a value indicating whether the **targetNamespace** of the specified [XmlSchema](../xmlschema/) is in the collection. |
| [Contains](./contains/)(const String\&) | Returns a value indicating whether a schema with the specified namespace is in the collection. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Copies all the [XmlSchema](../xmlschema/) objects from this collection into the given array starting at the given index. |
| [get_Count](./get_count/)() | Returns the number of namespaces defined in this collection. |
| [get_NameTable](./get_nametable/)() | Returns the default [XmlNameTable](../../system.xml/xmlnametable/) used by the [XmlSchemaCollection](./) when loading new schemas. |
| [GetEnumerator](./getenumerator/)() override | Provides support for iteration over the collection of schemas. |
| [idx_get](./idx_get/)(const String\&) | Returns the [XmlSchema](../xmlschema/) associated with the given namespace URI. |
| [XmlSchemaCollection](./xmlschemacollection/)() | Initializes a new instance of the [XmlSchemaCollection](./) class. |
| [XmlSchemaCollection](./xmlschemacollection/)(const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlSchemaCollection](./) class with the specified [XmlNameTable](../../system.xml/xmlnametable/). The [XmlNameTable](../../system.xml/xmlnametable/) is used when loading schemas. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks


## Deprecated
The XmlSchemaCollection class is obsolete. Use XmlSchemaSet instead. 

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
