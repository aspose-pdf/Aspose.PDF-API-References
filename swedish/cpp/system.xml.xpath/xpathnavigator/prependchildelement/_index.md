---
title: "System::Xml::XPath::XPathNavigator::PrependChildElement metod"
linktitle: "PrependChildElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::PrependChildElement metod. Skapar ett nytt barn-element i början av listan med barnnoder för den aktuella noden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymd-URI:n som anges med värdet som specificeras i C++."
type: docs
weight: 6700
url: /sv/cpp/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement method


Skapar ett nytt barn‑element i början av listan över barnnoder för den aktuella noden med det angivna namnrymdsprefixet, lokala namnet, namnrymd‑URI:n och det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
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
