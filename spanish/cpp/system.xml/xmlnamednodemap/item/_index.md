---
title: "System::Xml::XmlNamedNodeMap::Item method"
linktitle: "Item"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamedNodeMap::Item method. Recupera el nodo en el índice especificado en el XmlNamedNodeMap en C++."
type: docs
weight: 800
url: /es/cpp/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item method


Recupera el nodo en el índice especificado en el [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int32_t | La posición del índice del nodo a recuperar del [XmlNamedNodeMap](../). El índice comienza en cero; por lo tanto, el índice del primer nodo es 0 y el índice del último nodo es [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### ReturnValue

El [XmlNode](../../xmlnode/) en el índice especificado. Si **index** es menor que 0 o mayor o igual que el valor de [XmlNamedNodeMap::get_Count](../get_count/), se devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
