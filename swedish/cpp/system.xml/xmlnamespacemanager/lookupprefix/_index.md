---
title: "System::Xml::XmlNamespaceManager::LookupPrefix method"
linktitle: "LookupPrefix"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamespaceManager::LookupPrefix method. Hittar prefixen som deklarerats för den angivna namnutrymmes-URI:n i C++."
type: docs
weight: 900
url: /sv/cpp/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix method


Hittar prefixet som deklarerats för den angivna namnrymdens URI.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const String\& | Namnutrymmet att lösa upp för prefixen. |

### ReturnValue

Den matchande prefixen. Om det inte finns någon mappad prefix, returnerar metoden [String::Empty](../../../system/string/empty/). Om ett null‑värde tillhandahålls, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
