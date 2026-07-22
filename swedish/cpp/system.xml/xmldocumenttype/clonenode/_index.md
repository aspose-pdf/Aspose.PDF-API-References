---
title: "System::Xml::XmlDocumentType::CloneNode metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocumentType::CloneNode metod. Skapar en duplicering av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att bara klona själva noden. För dokumenttypnoder inkluderar den klonade noden alltid delträdet, oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
