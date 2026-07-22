---
title: "System::Xml::XPath::XPathNavigator::AppendChildElement metod"
linktitle: "AppendChildElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::AppendChildElement metod. Skapar en ny barn‑elementnod i slutet av listan med barnnoder för den aktuella noden med det angivna namnrymdsprefixet, det lokala namnet och den angivna namnrymd‑URI:n med det värde som anges i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement method


Skapar en ny barn‑elementnod i slutet av listan med barnnoder för den aktuella noden med namnrymdsprefix, lokalt namn och namnrymd‑URI som anges med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Namnrymdsprefixet för den nya barn‑elementnoden (om något). |
| localName | String | Det lokala namnet på den nya barn‑elementnoden (om något). |
| namespaceURI | String | Namnrymd‑URI:n för den nya barn‑elementnoden (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | String | Värdet för den nya underordnade elementnoden. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
