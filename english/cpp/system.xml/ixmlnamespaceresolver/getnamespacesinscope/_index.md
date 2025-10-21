---
title: System::Xml::IXmlNamespaceResolver::GetNamespacesInScope method
linktitle: GetNamespacesInScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::IXmlNamespaceResolver::GetNamespacesInScope method. Returns a collection of defined prefix-namespace mappings that are currently in scope in C++.'
type: docs
weight: 100
url: /cpp/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope method


Returns a collection of defined prefix-namespace mappings that are currently in scope.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| scope | XmlNamespaceScope | An [XmlNamespaceScope](../../xmlnamespacescope/) value that specifies the type of namespace nodes to return. |

### ReturnValue

An IDictionary collection that contains the current in-scope namespaces.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
