---
title: System::Xml::XmlTextReader::GetNamespacesInScope method
linktitle: GetNamespacesInScope
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::GetNamespacesInScope method. Returns a collection that contains all namespaces currently in-scope in C++.'
type: docs
weight: 3400
url: /cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope method


Returns a collection that contains all namespaces currently in-scope.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| scope | XmlNamespaceScope | An [XmlNamespaceScope](../../xmlnamespacescope/) value that specifies the type of namespace nodes to return. |

### ReturnValue

An IDictionary object that contains all the current in-scope namespaces. If the reader is not positioned on an element, an empty dictionary (no namespaces) is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
