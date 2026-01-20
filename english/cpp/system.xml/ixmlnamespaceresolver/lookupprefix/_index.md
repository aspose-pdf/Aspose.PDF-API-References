---
title: System::Xml::IXmlNamespaceResolver::LookupPrefix method
linktitle: LookupPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::IXmlNamespaceResolver::LookupPrefix method. Returns the prefix that is mapped to the specified namespace URI in C++.'
type: docs
weight: 300
url: /cpp/system.xml/ixmlnamespaceresolver/lookupprefix/
---
## IXmlNamespaceResolver::LookupPrefix method


Returns the prefix that is mapped to the specified namespace URI.

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupPrefix(const String &namespaceName)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| namespaceName | const String\& | The namespace URI whose prefix you wish to find. |

### ReturnValue

The prefix that is mapped to the namespace URI; **nullptr** if the namespace URI is not mapped to a prefix.

## See Also

* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
