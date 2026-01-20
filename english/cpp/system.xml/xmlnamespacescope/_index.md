---
title: System::Xml::XmlNamespaceScope enum
linktitle: XmlNamespaceScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceScope enum. Defines the namespace scope in C++.'
type: docs
weight: 5900
url: /cpp/system.xml/xmlnamespacescope/
---
## XmlNamespaceScope enum


Defines the namespace scope.

```cpp
enum class XmlNamespaceScope
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| All | 0 | All namespaces defined in the scope of the current node. This includes the xmlns:xml namespace which is always declared implicitly. The order of the namespaces returned is not defined. |
| ExcludeXml | 1 | All namespaces defined in the scope of the current node, excluding the xmlns:xml namespace, which is always declared implicitly. The order of the namespaces returned is not defined. |
| Local | 2 | All namespaces that are defined locally at the current node. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
