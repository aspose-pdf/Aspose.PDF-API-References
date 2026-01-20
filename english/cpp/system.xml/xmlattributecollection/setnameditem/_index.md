---
title: System::Xml::XmlAttributeCollection::SetNamedItem method
linktitle: SetNamedItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttributeCollection::SetNamedItem method. Adds an XmlNode using its XmlNode::get_Name result in C++.'
type: docs
weight: 1000
url: /cpp/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem method


Adds an [XmlNode](../../xmlnode/) using its [XmlNode::get_Name](../../xmlnode/get_name/) result.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | An attribute node to store in this collection. The node will later be accessible using the name of the node. If a node with that name is already present in the collection, it is replaced by the new one; otherwise, the node is appended to the end of the collection. |

### ReturnValue

If the **node** replaces an existing node with the same name, the old node is returned; otherwise, the added node is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
