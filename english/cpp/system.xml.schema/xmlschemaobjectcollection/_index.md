---
title: System::Xml::Schema::XmlSchemaObjectCollection class
linktitle: XmlSchemaObjectCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaObjectCollection class. A collection of XmlSchemaObjects in C++.'
type: docs
weight: 5100
url: /cpp/system.xml.schema/xmlschemaobjectcollection/
---
## XmlSchemaObjectCollection class


A collection of XmlSchemaObjects.

```cpp
class XmlSchemaObjectCollection : public System::Collections::CollectionBase<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const SharedPtr\<XmlSchemaObject\>\&) | Adds an [XmlSchemaObject](../xmlschemaobject/) to the [XmlSchemaObjectCollection](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchemaObject\>\&) | Indicates if the specified [XmlSchemaObject](../xmlschemaobject/) is in the [XmlSchemaObjectCollection](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>\&, int32_t) | Copies all the XmlSchemaObjects from the collection into the given array, starting at the given index. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for iterating through the XmlSchemaObjects contained in the [XmlSchemaObjectCollection](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Returns the [XmlSchemaObject](../xmlschemaobject/) at the specified index. |
| virtual [idx_set](./idx_set/)(int32_t, SharedPtr\<XmlSchemaObject\>) | Sets the [XmlSchemaObject](../xmlschemaobject/) at the specified index. |
| [IndexOf](./indexof/)(const SharedPtr\<XmlSchemaObject\>\&) | Returns the collection index corresponding to the specified [XmlSchemaObject](../xmlschemaobject/). |
| [Insert](./insert/)(int32_t, const SharedPtr\<XmlSchemaObject\>\&) | Inserts an [XmlSchemaObject](../xmlschemaobject/) to the [XmlSchemaObjectCollection](./). |
| [Remove](./remove/)(const SharedPtr\<XmlSchemaObject\>\&) | Removes an [XmlSchemaObject](../xmlschemaobject/) from the [XmlSchemaObjectCollection](./). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)() | Initializes a new instance of the [XmlSchemaObjectCollection](./) class. |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)(const SharedPtr\<XmlSchemaObject\>\&) | Initializes a new instance of the [XmlSchemaObjectCollection](./) class that takes an [XmlSchemaObject](../xmlschemaobject/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [CollectionBase](../../system.collections/collectionbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
