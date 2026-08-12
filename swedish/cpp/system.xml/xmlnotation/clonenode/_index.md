---
title: "System::Xml::XmlNotation::CloneNode metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNotation::CloneNode metod. Skapar en duplicering av denna nod. Notationsnoder kan inte klonas. Att anropa denna metod på ett XmlNotation-objekt kastar ett undantag i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode method


Skapar en duplikat av den här noden. Notationsnoder kan inte klonas. Att anropa den här metoden på ett [XmlNotation](../)-objekt kastar ett undantag.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att klona endast noden själv. |

### ReturnValue

En [XmlNode](../../xmlnode/)-kopia av noden som metoden anropas från.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
