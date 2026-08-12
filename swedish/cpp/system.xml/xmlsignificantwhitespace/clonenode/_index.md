---
title: "System::Xml::XmlSignificantWhitespace::CloneNode‑metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlSignificantWhitespace::CloneNode‑metod. Skapar en duplicering av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att bara klona själva noden. För betydande blankstegsnoder inkluderar den klonade noden alltid datavärdet, oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
