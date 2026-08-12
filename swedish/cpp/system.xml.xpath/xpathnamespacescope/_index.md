---
title: "System::Xml::XPath::XPathNamespaceScope enum"
linktitle: "XPathNamespaceScope"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNamespaceScope enum. Definierar namnrymdens omfattning i C++."
type: docs
weight: 1000
url: /sv/cpp/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum


Definierar namnrymdens omfattning.

```cpp
enum class XPathNamespaceScope
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Alla | 0 | Returnerar alla namnrymder som definierats i omfattningen för den aktuella noden. Detta inkluderar **xmlns:xml**‑namnrymden som alltid deklareras implicit. Ordningen på de returnerade namnrymderna är inte definierad. |
| ExcludeXml | 1 | Returnerar alla namnrymder som definierats i omfattningen för den aktuella noden, exklusive **xmlns:xml**‑namnrymden. **xmlns:xml**‑namnrymden deklareras alltid implicit. Ordningen på de returnerade namnrymderna är inte definierad. |
| Lokal | 2 | Returnerar alla namnrymder som definierats lokalt på den aktuella noden. |

## Se även

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
