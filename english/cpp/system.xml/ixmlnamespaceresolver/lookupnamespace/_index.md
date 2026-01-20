---
title: System::Xml::IXmlNamespaceResolver::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::IXmlNamespaceResolver::LookupNamespace method. Returns the namespace URI mapped to the specified prefix in C++.'
type: docs
weight: 200
url: /cpp/system.xml/ixmlnamespaceresolver/lookupnamespace/
---
## IXmlNamespaceResolver::LookupNamespace method


Returns the namespace URI mapped to the specified prefix.

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupNamespace(const String &prefix)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you wish to find. |

### ReturnValue

The namespace URI that is mapped to the prefix; **nullptr** if the prefix is not mapped to a namespace URI.

## See Also

* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
