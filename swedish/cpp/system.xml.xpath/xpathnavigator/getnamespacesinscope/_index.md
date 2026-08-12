---
title: "System::Xml::XPath::XPathNavigator::GetNamespacesInScope metod"
linktitle: "GetNamespacesInScope"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::GetNamespacesInScope metod. Returnerar de namnrymder som är i räckhåll för den aktuella noden i C++."
type: docs
weight: 4000
url: /sv/cpp/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope method


Returnerar de namnrymder som är i omfång för den aktuella noden.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scope | XmlNamespaceScope | Ett [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) värde som specificerar namnrymderna att returnera. |

### ReturnValue

En IDictionary-samling av namnrymdsnamn som nycklas med prefix.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
