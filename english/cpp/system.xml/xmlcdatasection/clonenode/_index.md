---
title: System::Xml::XmlCDataSection::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlCDataSection::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. Because CDATA nodes do not have children, regardless of the parameter setting, the cloned node will always include the data content. |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
