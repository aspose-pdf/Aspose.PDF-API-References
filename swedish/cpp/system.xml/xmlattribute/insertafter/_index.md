---
title: "System::Xml::XmlAttribute::InsertAfter metod"
linktitle: "InsertAfter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttribute::InsertAfter metod. Infogar den angivna noden omedelbart efter den angivna referensnoden i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter method


Infogar den angivna noden omedelbart efter den angivna referensnoden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Den [XmlNode](../../xmlnode/) att infoga. |
| refChild | SharedPtr\<XmlNode\> | Den [XmlNode](../../xmlnode/) som är referensnoden. **newChild** placeras efter **refChild**. |

### ReturnValue

Den [XmlNode](../../xmlnode/) som infogades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
