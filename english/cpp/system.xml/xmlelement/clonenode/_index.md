---
title: System::Xml::XmlElement::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself (and its attributes if the node is an [XmlElement](../)). |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
