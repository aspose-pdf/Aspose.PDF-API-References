---
title: "System::Xml::XmlNode::SelectSingleNode metod"
linktitle: "SelectSingleNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::SelectSingleNode metod. Väljer den första XmlNode som matchar XPath-uttrycket i C++."
type: docs
weight: 3900
url: /sv/cpp/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method


Väljer den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/) uttrycket.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const String\& | Det [XPath](../../../system.xml.xpath/) uttrycket. |

### ReturnValue

Den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/) frågan eller **nullptr** om ingen matchande nod hittas.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Väljer den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/) uttrycket. Alla prefix som finns i [XPath](../../../system.xml.xpath/) uttrycket löses upp med den tillhandahållna [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const String\& | Det [XPath](../../../system.xml.xpath/) uttrycket. |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | En [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att lösa namnrymder för prefix i [XPath](../../../system.xml.xpath/) uttrycket. |

### ReturnValue

Den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/) frågan eller **nullptr** om ingen matchande nod hittas.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
