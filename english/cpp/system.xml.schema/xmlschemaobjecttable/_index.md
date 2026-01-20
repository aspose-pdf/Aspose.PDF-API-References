---
title: System::Xml::Schema::XmlSchemaObjectTable class
linktitle: XmlSchemaObjectTable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaObjectTable class. Provides the collections for contained elements in the XmlSchema class (for example, Attributes, AttributeGroups, Elements, and so on) in C++.'
type: docs
weight: 5300
url: /cpp/system.xml.schema/xmlschemaobjecttable/
---
## XmlSchemaObjectTable class


Provides the collections for contained elements in the [XmlSchema](../xmlschema/) class (for example, Attributes, AttributeGroups, Elements, and so on).

```cpp
class XmlSchemaObjectTable : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<SharedPtr<System::Xml::XmlQualifiedName>, SharedPtr<System::Xml::Schema::XmlSchemaObject>>>
```

## Methods

| Method | Description |
| --- | --- |
| [Contains](./contains/)(const SharedPtr\<XmlQualifiedName\>\&) | Determines if the qualified name specified exists in the collection. |
| [get_Count](./get_count/)() | Returns the number of items contained in the [XmlSchemaObjectTable](./). |
| [get_Names](./get_names/)() | Returns a collection of all the named elements in the [XmlSchemaObjectTable](./). |
| [get_Values](./get_values/)() | Returns a collection of all the values for all the elements in the [XmlSchemaObjectTable](./). |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that can iterate through the [XmlSchemaObjectTable](./). |
| [idx_get](./idx_get/)(const SharedPtr\<XmlQualifiedName\>\&) | Returns the element in the [XmlSchemaObjectTable](./) specified by qualified name. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
