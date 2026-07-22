---
title: "System::Xml::XmlElement::CloneNode method"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlElement::CloneNode metod. Skapar en duplikat av den här noden i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att klona endast noden själv (och dess attribut om noden är ett [XmlElement](../)). |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
