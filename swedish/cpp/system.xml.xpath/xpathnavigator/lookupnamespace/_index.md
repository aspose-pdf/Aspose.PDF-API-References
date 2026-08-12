---
title: "System::Xml::XPath::XPathNavigator::LookupNamespace‑metod"
linktitle: "LookupNamespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::LookupNamespace‑metod. Returnerar namnrymdens URI för det angivna prefixet i C++."
type: docs
weight: 4700
url: /sv/cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace method


Returnerar namnrymdens URI för det angivna prefixet.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixen vars namnutrymmes-URI du vill lösa upp. För att matcha standardnamnutrymmet, skicka [String::Empty](../../../system/string/empty/). |

### ReturnValue

En [String](../../../system/string/) som innehåller namnrymdens URI som tilldelats det angivna namnrymdsprefixet; **nullptr** om ingen namnrymds‑URI är tilldelad till det angivna prefixet. Den returnerade [String](../../../system/string/) är atomiserad.

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
