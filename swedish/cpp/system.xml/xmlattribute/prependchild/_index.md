---
title: "System::Xml::XmlAttribute::PrependChild metod"
linktitle: "PrependChild"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttribute::PrependChild metod. Lägger till den angivna noden i början av listan med barnnoder för den här noden i C++."
type: docs
weight: 1600
url: /sv/cpp/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild method


Lägger till den angivna noden i början av listan över barnnoder för denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Den [XmlNode](../../xmlnode/) att lägga till. Om den är ett [XmlDocumentFragment](../../xmldocumentfragment/), flyttas hela innehållet i dokumentfragmentet in i barnlistan för den här noden. |

### ReturnValue

Den [XmlNode](../../xmlnode/) som lades till.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
