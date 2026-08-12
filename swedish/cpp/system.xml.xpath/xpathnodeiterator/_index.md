---
title: "System::Xml::XPath::XPathNodeIterator klass"
linktitle: "XPathNodeIterator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNodeIterator-klass. Tillhandahåller en iterator över en vald uppsättning noder i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml.xpath/xpathnodeiterator/
---
## XPathNodeIterator class


Tillhandahåller en iterator över en vald mängd noder.

```cpp
class XPathNodeIterator : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XPath::XPathNavigator>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Clone](./clone/)() | När den åsidosätts i en avledd klass returneras en klon av detta [XPathNodeIterator](./)-objekt. |
| virtual [get_Count](./get_count/)() | Returnerar indexet för den sista noden i den valda uppsättningen noder. |
| virtual [get_Current](./get_current/)() | När den åsidosätts i en avledd klass hämtas [XPathNavigator](../xpathnavigator/)-objektet för detta [XPathNodeIterator](./), placerat på den aktuella kontextnoden. |
| virtual [get_CurrentPosition](./get_currentposition/)() | När den åsidosätts i en avledd klass hämtas indexet för den aktuella positionen i den valda uppsättningen noder. |
| [GetEnumerator](./getenumerator/)() override | Returnerar ett IEnumerator-objekt för att iterera genom den valda noduppsättningen. |
| virtual [MoveNext](./movenext/)() | När den åsidosätts i en avledd klass flyttas [XPathNavigator](../xpathnavigator/)-objektet som returneras av metoden [XPathNodeIterator::get_Current](./get_current/) till nästa nod i den valda noduppsättningen. |
| [XPathNodeIterator](./xpathnodeiterator/)() | Initierar en ny instans av [XPathNodeIterator](./)-klassen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
