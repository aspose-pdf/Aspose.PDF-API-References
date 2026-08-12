---
title: "System::Xml::XmlAttributeCollection::SetNamedItem‑metod"
linktitle: "SetNamedItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttributeCollection::SetNamedItem‑metod. Lägger till ett XmlNode med hjälp av dess XmlNode::get_Name‑resultat i C++."
type: docs
weight: 1000
url: /sv/cpp/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem method


Lägger till ett [XmlNode](../../xmlnode/) med hjälp av dess [XmlNode::get_Name](../../xmlnode/get_name/)‑resultat.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | Ett attributnod att lagra i den här samlingen. Noden kommer senare att vara åtkomlig med nodens namn. Om en nod med det namnet redan finns i samlingen ersätts den med den nya; annars läggs noden till i slutet av samlingen. |

### ReturnValue

Om **node** ersätter en befintlig nod med samma namn returneras den gamla noden; annars returneras den tillagda noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
