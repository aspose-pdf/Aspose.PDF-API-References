---
title: System::Xml::Schema::XmlSchemaSimpleTypeList class
linktitle: XmlSchemaSimpleTypeList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleTypeList class. Represents the list element from XML Schema as specified by the World Wide Web Consortium (W3C). This class can be used to define a simpleType element as a list of values of a specified data type in C++.'
type: docs
weight: 6400
url: /cpp/system.xml.schema/xmlschemasimpletypelist/
---
## XmlSchemaSimpleTypeList class


Represents the **list** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class can be used to define a **simpleType** element as a list of values of a specified data type.

```cpp
class XmlSchemaSimpleTypeList : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaseItemType](./get_baseitemtype/)() | Returns the [XmlSchemaSimpleType](../xmlschemasimpletype/) representing the type of the **simpleType** element based on the [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) and [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) values of the simple type. |
| [get_ItemType](./get_itemtype/)() | Returns the **simpleType** element that is derived from the type specified by the base value. |
| [get_ItemTypeName](./get_itemtypename/)() | Returns the name of a built-in data type or **simpleType** element defined in this schema (or another schema indicated by the specified namespace). |
| [set_BaseItemType](./set_baseitemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets the [XmlSchemaSimpleType](../xmlschemasimpletype/) representing the type of the **simpleType** element based on the [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) and [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) values of the simple type. |
| [set_ItemType](./set_itemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Sets the **simpleType** element that is derived from the type specified by the base value. |
| [set_ItemTypeName](./set_itemtypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of a built-in data type or **simpleType** element defined in this schema (or another schema indicated by the specified namespace). |
| [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/)() | Initializes a new instance of the [XmlSchemaSimpleTypeList](./) class. |
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
