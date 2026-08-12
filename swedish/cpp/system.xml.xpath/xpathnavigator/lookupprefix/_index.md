---
title: "System::Xml::XPath::XPathNavigator::LookupPrefix metod"
linktitle: "LookupPrefix"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::LookupPrefix metod. Returnerar prefixet som deklarerats för den angivna namnrymdens URI i C++."
type: docs
weight: 4800
url: /sv/cpp/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix method


Returnerar prefixet som deklarerats för den angivna namespace‑URI:n.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceURI | const String\& | Namnrymdens URI att lösa för prefixet. |

### ReturnValue

En [String](../../../system/string/) som innehåller namnrymdsprefixet som tilldelats den angivna namnrymdens URI; annars [String::Empty](../../../system/string/empty/) om inget prefix är tilldelat den angivna namnrymdens URI. Den returnerade [String](../../../system/string/) är atomiserad.

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
