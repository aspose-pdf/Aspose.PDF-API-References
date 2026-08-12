---
title: "System::Xml::XmlNamespaceManager::GetNamespacesInScope metod"
linktitle: "GetNamespacesInScope"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamespaceManager::GetNamespacesInScope metod. Returnerar en samling av namnrymdsnamn nycklade efter prefix som kan användas för att enumerera de namnrymder som för närvarande är i aktuell omfattning i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope method


Returnerar en samling av namnrymdnamn nycklade efter prefix som kan användas för att enumerera namnrymderna som för närvarande är i omfång.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| omfattning | XmlNamespaceScope | Ett uppräkningsvärde som specificerar vilken typ av namnrymdsnoder som ska returneras. |

### ReturnValue

En samling av namnrymds- och prefixpar som för närvarande är i omfattning.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
