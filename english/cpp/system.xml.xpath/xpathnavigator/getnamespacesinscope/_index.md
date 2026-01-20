---
title: System::Xml::XPath::XPathNavigator::GetNamespacesInScope method
linktitle: GetNamespacesInScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::GetNamespacesInScope method. Returns the in-scope namespaces of the current node in C++.'
type: docs
weight: 4000
url: /cpp/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope method


Returns the in-scope namespaces of the current node.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| scope | XmlNamespaceScope | An [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) value specifying the namespaces to return. |

### ReturnValue

An IDictionary collection of namespace names keyed by prefix.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
