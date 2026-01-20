---
title: System::Xml::XmlEntity::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlEntity::CloneNode method. Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an XmlEntity object throws an exception in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode method


Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an [XmlEntity](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. |

### ReturnValue

A copy of the [XmlNode](../../xmlnode/) from which the method is called.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
