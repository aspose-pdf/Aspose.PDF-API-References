---
title: "System::Xml::XmlNamespaceManager::AddNamespace metod"
linktitle: "AddNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamespaceManager::AddNamespace metod. Lägger till den angivna namnrymden i samlingen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace method


Lägger till den angivna namnrymden i samlingen.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Prefixet att associera med den namnrymd som läggs till. Använd [String::Empty](../../../system/string/empty/) för att lägga till en standardnamnrymd. Om [XmlNamespaceManager](../) kommer att användas för att lösa namnrymder i ett XML Path Language‑uttryck ([XPath](../../../system.xml.xpath/)), måste ett prefix specificeras. Om ett [XPath](../../../system.xml.xpath/)‑uttryck inte innehåller ett prefix, antas att namnrymdens Uniform Resource Identifier (URI) är den tomma namnrymden. För mer information om [XPath](../../../system.xml.xpath/)‑uttryck och [XmlNamespaceManager](../), se metoderna XmlNode::SelectNodes(String) och XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | String | Namnrymden att lägga till. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
