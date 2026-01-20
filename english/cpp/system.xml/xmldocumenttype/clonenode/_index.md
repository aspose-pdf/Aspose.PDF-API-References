---
title: System::Xml::XmlDocumentType::CloneNode method
linktitle: CloneNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocumentType::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For document type nodes, the cloned node always includes the subtree, regardless of the parameter setting. |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
