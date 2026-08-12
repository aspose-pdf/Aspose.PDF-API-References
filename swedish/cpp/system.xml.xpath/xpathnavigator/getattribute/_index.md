---
title: "System::Xml::XPath::XPathNavigator::GetAttribute metod"
linktitle: "GetAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::GetAttribute metod. Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI i C++."
type: docs
weight: 3800
url: /sv/cpp/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute method


Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. **localName** är skiftlägeskänsligt. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

En [String](../../../system/string/) som innehåller värdet på det angivna attributet; [String::Empty](../../../system/string/empty/) om ett matchande attribut inte hittas, eller om [XPathNavigator](../) inte är placerad på en elementnod.

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
