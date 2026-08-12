---
title: "System::Xml::XmlNamespaceManager::LookupNamespace method"
linktitle: "LookupNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamespaceManager::LookupNamespace method. Returnerar namnutrymmes-URI för den angivna prefixen i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace method


Returnerar namnrymdens URI för det angivna prefixet.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixen vars namnutrymmes-URI du vill lösa upp. För att matcha standardnamnutrymmet, skicka [String::Empty](../../../system/string/empty/). |

### ReturnValue

Namnutrymmes-URI för **prefix** eller **nullptr** om det inte finns något mappat namnutrymme. Den returnerade strängen är atomiserad. För mer information om atomiserade strängar, se klassen [XmlNameTable](../../xmlnametable/).

## Se även

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
