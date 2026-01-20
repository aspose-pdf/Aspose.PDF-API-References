---
title: System::Xml::XmlNotation::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNotation::CloneNode method. Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an XmlNotation object throws an exception in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode method


Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an [XmlNotation](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. |

### ReturnValue

A [XmlNode](../../xmlnode/) copy of the node from which the method is called.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
