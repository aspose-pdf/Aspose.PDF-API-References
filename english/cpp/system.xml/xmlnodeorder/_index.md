---
title: System::Xml::XmlNodeOrder enum
linktitle: XmlNodeOrder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeOrder enum. Describes the document order of a node compared to a second node in C++.'
type: docs
weight: 6100
url: /cpp/system.xml/xmlnodeorder/
---
## XmlNodeOrder enum


Describes the document order of a node compared to a second node.

```cpp
enum class XmlNodeOrder
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Before | 0 | The current node of this navigator is before the current node of the supplied navigator. |
| After | 1 | The current node of this navigator is after the current node of the supplied navigator. |
| Same | 2 | The two navigators are positioned on the same node. |
| Unknown | 3 | The node positions cannot be determined in document order, relative to each other. This could occur if the two nodes reside in different trees. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
