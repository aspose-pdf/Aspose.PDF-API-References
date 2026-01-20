---
title: System::Xml::XmlNamedNodeMap::Item method
linktitle: Item
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamedNodeMap::Item method. Retrieves the node at the specified index in the XmlNamedNodeMap in C++.'
type: docs
weight: 800
url: /cpp/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item method


Retrieves the node at the specified index in the [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index position of the node to retrieve from the [XmlNamedNodeMap](../). The index is zero-based; therefore, the index of the first node is 0 and the index of the last node is [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### ReturnValue

The [XmlNode](../../xmlnode/) at the specified index. If **index** is less than 0 or greater than or equal to the [XmlNamedNodeMap::get_Count](../get_count/) value, **nullptr** is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
