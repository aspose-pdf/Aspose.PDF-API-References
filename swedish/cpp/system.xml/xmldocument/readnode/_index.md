---
title: "System::Xml::XmlDocument::ReadNode metod"
linktitle: "ReadNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::ReadNode‑metod. Skapar ett XmlNode‑objekt baserat på informationen i XmlReader. Läsaren måste vara placerad på en nod eller ett attribut i C++."
type: docs
weight: 3600
url: /sv/cpp/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode method


Skapar ett [XmlNode](../../xmlnode/)‑objekt baserat på informationen i [XmlReader](../../xmlreader/). Läsaren måste vara placerad på en nod eller ett attribut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läsare | SharedPtr\<XmlReader\> | XML‑källan. |

### ReturnValue

Det nya [XmlNode](../../xmlnode/) eller **nullptr** om inga fler noder finns.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
