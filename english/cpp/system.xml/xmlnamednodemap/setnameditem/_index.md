---
title: System::Xml::XmlNamedNodeMap::SetNamedItem method
linktitle: SetNamedItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamedNodeMap::SetNamedItem method. Adds an XmlNode using its XmlNode::get_Name value in C++.'
type: docs
weight: 1000
url: /cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Adds an [XmlNode](../../xmlnode/) using its [XmlNode::get_Name](../../xmlnode/get_name/) value.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | An [XmlNode](../../xmlnode/) to store in the [XmlNamedNodeMap](../). If a node with that name is already present in the map, it is replaced by the new one. |

### ReturnValue

If the **node** replaces an existing node with the same name, the old node is returned; otherwise, **nullptr** is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
