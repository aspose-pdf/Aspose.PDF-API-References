---
title: System::Xml::XmlNamedNodeMap class
linktitle: XmlNamedNodeMap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamedNodeMap class. Represents a collection of nodes that can be accessed by name or index in C++.'
type: docs
weight: 2200
url: /cpp/system.xml/xmlnamednodemap/
---
## XmlNamedNodeMap class


Represents a collection of nodes that can be accessed by name or index.

```cpp
class XmlNamedNodeMap : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>
```

## Methods

| Method | Description |
| --- | --- |
| [begin](./begin/)() const | Gets iterator to the first element of collection. |
| [cbegin](./cbegin/)() const | Gets iterator to the first element of collection. |
| [cend](./cend/)() const | Gets iterator for a non-existent element behind the last element of the collection. |
| [end](./end/)() const | Gets iterator for a non-existent element behind the last element of the collection. |
| virtual [get_Count](./get_count/)() | Returns the number of nodes in the [XmlNamedNodeMap](./). |
| [GetEnumerator](./getenumerator/)() override | Provides support for iteration over the collection of nodes in the [XmlNamedNodeMap](./). |
| virtual [GetNamedItem](./getnameditem/)(String) | Retrieves an [XmlNode](../xmlnode/) specified by name. |
| virtual [GetNamedItem](./getnameditem/)(String, String) | Retrieves a node with the matching [XmlNode::get_LocalName](../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) values. |
| virtual [Item](./item/)(int32_t) | Retrieves the node at the specified index in the [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String) | Removes the node from the [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String, String) | Removes a node with the matching [XmlNode::get_LocalName](../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) values. |
| virtual [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) | Adds an [XmlNode](../xmlnode/) using its [XmlNode::get_Name](../xmlnode/get_name/) value. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [iterator](./iterator/) | Iterator type. |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
