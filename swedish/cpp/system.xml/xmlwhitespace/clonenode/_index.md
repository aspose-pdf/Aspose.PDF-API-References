---
title: "System::Xml::XmlWhitespace::CloneNode metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWhitespace::CloneNode metod. Skapar en duplikat av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att klona endast noden själv. För blankstegsnoder inkluderar den klonade noden alltid datavärdet, oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
