---
title: "System::Xml::XmlNode::SelectNodes‑metod"
linktitle: "SelectNodes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::SelectNodes‑metod. Väljer en lista med noder som matchar XPath‑uttrycket i C++."
type: docs
weight: 3800
url: /sv/cpp/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


Väljer en lista med noder som matchar [XPath](../../../system.xml.xpath/)-uttrycket.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const String\& | Det [XPath](../../../system.xml.xpath/) uttrycket. |

### ReturnValue

En [XmlNodeList](../../xmlnodelist/) som innehåller en samling noder som matchar [XPath](../../../system.xml.xpath/)-frågan.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Väljer en lista med noder som matchar [XPath](../../../system.xml.xpath/)-uttrycket. Eventuella prefix som finns i [XPath](../../../system.xml.xpath/)-uttrycket löses upp med den medföljande [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const String\& | Det [XPath](../../../system.xml.xpath/) uttrycket. |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | En [XmlNamespaceManager](../../xmlnamespacemanager/) att använda för att lösa namnrymder för prefix i [XPath](../../../system.xml.xpath/) uttrycket. |

### ReturnValue

En [XmlNodeList](../../xmlnodelist/) som innehåller en samling noder som matchar [XPath](../../../system.xml.xpath/)-frågan.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
