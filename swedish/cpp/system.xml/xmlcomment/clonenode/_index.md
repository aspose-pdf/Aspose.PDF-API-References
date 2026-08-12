---
title: "System::Xml::XmlComment::CloneNode metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlComment::CloneNode metod. Skapar en duplicering av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att bara klona själva noden. Eftersom kommentarsnoder inte har barn, inkluderar den klonade noden alltid textinnehållet, oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlComment](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
