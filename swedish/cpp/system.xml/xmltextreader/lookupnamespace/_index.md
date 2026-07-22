---
title: "System::Xml::XmlTextReader::LookupNamespace‑metod"
linktitle: "LookupNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::LookupNamespace‑metod. Löser upp ett namnrymdsprefix i den aktuella elementets omfattning i C++."
type: docs
weight: 3700
url: /sv/cpp/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace method


Löser upp ett namnrymdsprefix i det aktuella elementets omfång.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixet vars namnrymd-URI du vill lösa. För att matcha standardnamnrymden, skicka en tom sträng. Denna sträng behöver inte atomiseras. |

### ReturnValue

Namnrymd-URI:n som prefixet mappar till eller **nullptr** om ingen matchande prefix hittas.

## Se även

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
