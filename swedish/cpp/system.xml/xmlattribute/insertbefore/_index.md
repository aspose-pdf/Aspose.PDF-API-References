---
title: "System::Xml::XmlAttribute::InsertBefore metod"
linktitle: "InsertBefore"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttribute::InsertBefore metod. Infogar den angivna noden omedelbart före den angivna referensnoden i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore method


Infogar den angivna noden omedelbart före den angivna referensnoden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Den [XmlNode](../../xmlnode/) att infoga. |
| refChild | SharedPtr\<XmlNode\> | Den [XmlNode](../../xmlnode/) som är referensnoden. **newChild** placeras före den här noden. |

### ReturnValue

Den [XmlNode](../../xmlnode/) som infogades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
