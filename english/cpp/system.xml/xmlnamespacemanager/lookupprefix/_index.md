---
title: System::Xml::XmlNamespaceManager::LookupPrefix method
linktitle: LookupPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceManager::LookupPrefix method. Finds the prefix declared for the given namespace URI in C++.'
type: docs
weight: 900
url: /cpp/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix method


Finds the prefix declared for the given namespace URI.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const String\& | The namespace to resolve for the prefix. |

### ReturnValue

The matching prefix. If there is no mapped prefix, the method returns [String::Empty](../../../system/string/empty/). If a null value is supplied, then **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
