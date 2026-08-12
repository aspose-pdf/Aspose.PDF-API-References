---
title: "System::Xml::XmlTextReader::GetNamespacesInScope metod"
linktitle: "GetNamespacesInScope"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::GetNamespacesInScope metod. Returnerar en samling som innehåller alla namnrymder som för närvarande är i scope i C++."
type: docs
weight: 3400
url: /sv/cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope method


Returnerar en samling som innehåller alla namnrymder som för närvarande är i räckvidd.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scope | XmlNamespaceScope | Ett [XmlNamespaceScope](../../xmlnamespacescope/)‑värde som specificerar vilken typ av namnrymdsnoder som ska returneras. |

### ReturnValue

Ett IDictionary‑objekt som innehåller alla aktuella namnrymder i scope. Om läsaren inte är placerad på ett element returneras en tom dictionary (inga namnrymder).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
