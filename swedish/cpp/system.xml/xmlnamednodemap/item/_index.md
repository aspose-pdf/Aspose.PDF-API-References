---
title: "System::Xml::XmlNamedNodeMap::Item metod"
linktitle: "Item"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamedNodeMap::Item metod. Hämtar noden på det angivna indexet i XmlNamedNodeMap i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item method


Hämtar noden på det angivna indexet i [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Indexpositionen för noden som ska hämtas från [XmlNamedNodeMap](../). Indexet är nollbaserat; därför är indexet för den första noden 0 och indexet för den sista noden är [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### ReturnValue

Den [XmlNode](../../xmlnode/) på det angivna indexet. Om **index** är mindre än 0 eller större än eller lika med värdet för [XmlNamedNodeMap::get_Count](../get_count/) returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
