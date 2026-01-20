---
title: System::Xml::XmlNodeList::Item method
linktitle: Item
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeList::Item method. Retrieves a node at the given index in C++.'
type: docs
weight: 400
url: /cpp/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item method


Retrieves a node at the given index.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The zero-based index into the list of nodes. |

### ReturnValue

The [XmlNode](../../xmlnode/) with the specified index in the collection. If **index** is greater than or equal to the number of nodes in the list, this returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
