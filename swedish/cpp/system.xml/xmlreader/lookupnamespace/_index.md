---
title: "System::Xml::XmlReader::LookupNamespace metod"
linktitle: "LookupNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::LookupNamespace metod. När den åsidosätts i en avledd klass löser den ett namnrymdsprefix i det aktuella elementets omfattning i C++."
type: docs
weight: 3100
url: /sv/cpp/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace method


När den åsidosätts i en avledd klass, löser den upp ett namnrymdspräfix i det aktuella elementets omfattning.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixet vars namnrymds-URI du vill lösa. För att matcha standardnamnrymden, skicka en tom sträng. |

### ReturnValue

Namnrymd-URI:n som prefixet mappar till eller **nullptr** om ingen matchande prefix hittas.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
