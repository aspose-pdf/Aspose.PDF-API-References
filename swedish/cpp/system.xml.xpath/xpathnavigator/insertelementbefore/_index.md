---
title: "System::Xml::XPath::XPathNavigator::InsertElementBefore‑metod"
linktitle: "InsertElementBefore"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::InsertElementBefore‑metod. Skapar ett nytt syskon‑element före den aktuella noden med det angivna namnrymdsprefixet, lokala namnet och namnrymds‑URI, samt det angivna värdet i C++."
type: docs
weight: 4400
url: /sv/cpp/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore method


Skapar ett nytt syskonelement före den aktuella noden med det angivna namespace‑prefixet, lokala namnet och den angivna namespace‑URI:n, med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Namnrymdsprefixet för det nya barnelementet (om något). |
| localName | String | Det lokala namnet för det nya barnelementet (om något). |
| namespaceURI | String | Namnrymdens URI för det nya barnelementet (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | String | Värdet för det nya underordnade elementet. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
