---
title: System::Xml::XmlNodeList::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeList::idx_get method. Returns a node at the given index in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get method


Returns a node at the given index.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The zero-based index into the list of nodes. |

### ReturnValue

The [XmlNode](../../xmlnode/) with the specified index in the collection. If index is greater than or equal to the number of nodes in the list, this returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
