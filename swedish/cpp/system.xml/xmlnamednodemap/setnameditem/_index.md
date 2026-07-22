---
title: "System::Xml::XmlNamedNodeMap::SetNamedItem‑metod"
linktitle: "SetNamedItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamedNodeMap::SetNamedItem‑metod. Lägger till en XmlNode med hjälp av dess XmlNode::get_Name‑värde i C++."
type: docs
weight: 1000
url: /sv/cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Lägger till en [XmlNode](../../xmlnode/) med hjälp av dess [XmlNode::get_Name](../../xmlnode/get_name/) värde.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | En [XmlNode](../../xmlnode/) att lagra i [XmlNamedNodeMap](../). Om en nod med det namnet redan finns i kartan ersätts den av den nya. |

### ReturnValue

Om **node** ersätter en befintlig nod med samma namn returneras den gamla noden; annars returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
