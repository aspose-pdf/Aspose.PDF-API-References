---
title: "System::Xml::XmlDeclaration::CloneNode metod"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDeclaration::CloneNode metod. Skapar en duplikat av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att klona endast noden själv. Eftersom [XmlDeclaration](../)-noder inte har barn, inkluderar den klonade noden alltid datavärdet, oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
