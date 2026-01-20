---
title: System::Xml::XmlNamespaceManager::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceManager::LookupNamespace method. Returns the namespace URI for the specified prefix in C++.'
type: docs
weight: 800
url: /cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace method


Returns the namespace URI for the specified prefix.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass [String::Empty](../../../system/string/empty/). |

### ReturnValue

The namespace URI for **prefix** or **nullptr** if there is no mapped namespace. The returned string is atomized. For more information on atomized strings, see the [XmlNameTable](../../xmlnametable/) class.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
