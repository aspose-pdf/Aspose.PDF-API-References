---
title: System::Xml::XmlNamespaceManager::GetNamespacesInScope method
linktitle: GetNamespacesInScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceManager::GetNamespacesInScope method. Returns a collection of namespace names keyed by prefix which can be used to enumerate the namespaces currently in scope in C++.'
type: docs
weight: 600
url: /cpp/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope method


Returns a collection of namespace names keyed by prefix which can be used to enumerate the namespaces currently in scope.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| scope | XmlNamespaceScope | An enumeration value that specifies the type of namespace nodes to return. |

### ReturnValue

A collection of namespace and prefix pairs currently in scope.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
