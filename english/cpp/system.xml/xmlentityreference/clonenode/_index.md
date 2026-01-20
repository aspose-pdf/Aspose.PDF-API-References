---
title: System::Xml::XmlEntityReference::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlEntityReference::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For [XmlEntityReference](../) nodes, this method always returns an entity reference node with no children. The replacement text is set when the node is inserted into a parent. |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
