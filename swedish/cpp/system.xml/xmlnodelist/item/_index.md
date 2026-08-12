---
title: "System::Xml::XmlNodeList::Item method"
linktitle: "Item"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeList::Item method. Hämtar en nod på det angivna indexet i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item method


Hämtar en nod på det angivna indexet.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Det nollbaserade indexet i listan av noder. |

### ReturnValue

Den [XmlNode](../../xmlnode/) med det angivna indexet i samlingen. Om **index** är större än eller lika med antalet noder i listan, returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
