---
title: "System::Xml::XmlAttributeCollection::InsertBefore metod"
linktitle: "InsertBefore"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttributeCollection::InsertBefore metod. Infogar det angivna attributet omedelbart före det angivna referensattributet i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore method


Infogar det angivna attributet omedelbart före det angivna referensattributet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | Attributet att infoga. |
| refNode | const SharedPtr\<XmlAttribute\>\& | Referensattributet. **newNode** placeras före **refNode**. |

### ReturnValue

Den [XmlAttribute](../../xmlattribute/) som ska infogas i samlingen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
