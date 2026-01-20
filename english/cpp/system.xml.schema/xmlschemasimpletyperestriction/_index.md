---
title: System::Xml::Schema::XmlSchemaSimpleTypeRestriction class
linktitle: XmlSchemaSimpleTypeRestriction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleTypeRestriction class. Represents the restriction element for simple types from XML Schema as specified by the World Wide Web Consortium (W3C). This class can be used restricting simpleType element in C++.'
type: docs
weight: 6500
url: /cpp/system.xml.schema/xmlschemasimpletyperestriction/
---
## XmlSchemaSimpleTypeRestriction class


Represents the **restriction** element for simple types from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class can be used restricting **simpleType** element.

```cpp
class XmlSchemaSimpleTypeRestriction : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaseType](./get_basetype/)() | Returns information on the base type. |
| [get_BaseTypeName](./get_basetypename/)() | Returns the name of the qualified base type. |
| [get_Facets](./get_facets/)() | Returns an [Xml](../../system.xml/)[Schema](../) facet. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets information on the base type. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the qualified base type. |
| [XmlSchemaSimpleTypeRestriction](./xmlschemasimpletyperestriction/)() | Initializes a new instance of the [XmlSchemaSimpleTypeRestriction](./) class. |
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
