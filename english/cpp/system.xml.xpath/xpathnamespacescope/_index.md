---
title: System::Xml::XPath::XPathNamespaceScope enum
linktitle: XPathNamespaceScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNamespaceScope enum. Defines the namespace scope in C++.'
type: docs
weight: 1000
url: /cpp/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum


Defines the namespace scope.

```cpp
enum class XPathNamespaceScope
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| All | 0 | Returns all namespaces defined in the scope of the current node. This includes the **xmlns:xml** namespace which is always declared implicitly. The order of the namespaces returned is not defined. |
| ExcludeXml | 1 | Returns all namespaces defined in the scope of the current node, excluding the **xmlns:xml** namespace. The **xmlns:xml** namespace is always declared implicitly. The order of the namespaces returned is not defined. |
| Local | 2 | Returns all namespaces that are defined locally at the current node. |

## See Also

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
