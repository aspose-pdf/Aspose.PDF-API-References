---
title: System::Xml::XmlDeclaration::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDeclaration::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. Because [XmlDeclaration](../) nodes do not have children, the cloned node always includes the data value, regardless of the parameter setting. |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
