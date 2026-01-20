---
title: System::Xml::XmlAttributeCollection class
linktitle: XmlAttributeCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttributeCollection class. Represents a collection of attributes that can be accessed by name or index in C++.'
type: docs
weight: 700
url: /cpp/system.xml/xmlattributecollection/
---
## XmlAttributeCollection class


Represents a collection of attributes that can be accessed by name or index.

```cpp
class XmlAttributeCollection : public System::Xml::XmlNamedNodeMap
```

## Methods

| Method | Description |
| --- | --- |
| [Append](./append/)(const SharedPtr\<XmlAttribute\>\&) | Inserts the specified attribute as the last node in the collection. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&, int32_t) | Copies all the [XmlAttribute](../xmlattribute/) objects from this collection into the given array. |
| [idx_get](./idx_get/)(int32_t) | Returns the attribute with the specified index. |
| [idx_get](./idx_get/)(const String\&) | Returns the attribute with the specified name. |
| [idx_get](./idx_get/)(const String\&, const String\&) | Returns the attribute with the specified local name and namespace Uniform Resource Identifier (URI). |
| [InsertAfter](./insertafter/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Inserts the specified attribute immediately after the specified reference attribute. |
| [InsertBefore](./insertbefore/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Inserts the specified attribute immediately before the specified reference attribute. |
| [Prepend](./prepend/)(const SharedPtr\<XmlAttribute\>\&) | Inserts the specified attribute as the first node in the collection. |
| [Remove](./remove/)(const SharedPtr\<XmlAttribute\>\&) | Removes the specified attribute from the collection. |
| [RemoveAll](./removeall/)() | Removes all attributes from the collection. |
| [RemoveAt](./removeat/)(int32_t) | Removes the attribute corresponding to the specified index from the collection. |
| [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) override | Adds an [XmlNode](../xmlnode/) using its [XmlNode::get_Name](../xmlnode/get_name/) result. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlNamedNodeMap](../xmlnamednodemap/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
