---
title: "System::Xml::XmlCDataSection::CloneNode method"
linktitle: "CloneNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlCDataSection::CloneNode method. Skapar en duplikat av denna nod i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode method


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | bool | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att klona endast noden själv. Eftersom CDATA‑noder inte har barn, kommer den klonade noden alltid att inkludera datainnehållet oavsett parameterinställning. |

### ReturnValue

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
