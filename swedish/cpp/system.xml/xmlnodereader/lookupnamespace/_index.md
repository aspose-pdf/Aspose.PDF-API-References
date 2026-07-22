---
title: "System::Xml::XmlNodeReader::LookupNamespace-metod"
linktitle: "LookupNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::LookupNamespace metod. Löser en namnrymdsprefix i det aktuella elementets omfattning i C++."
type: docs
weight: 2500
url: /sv/cpp/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace method


Löser upp ett namnrymdsprefix i det aktuella elementets omfång.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixet vars namnrymd-URI du vill lösa. För att matcha standardnamnrymden, skicka en tom sträng. Denna sträng behöver inte atomiseras. |

### ReturnValue

Namnrymd-URI:n som prefixet mappar till eller **nullptr** om ingen matchande prefix hittas.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
