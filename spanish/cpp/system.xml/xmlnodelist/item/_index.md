---
title: "System::Xml::XmlNodeList::Item method"
linktitle: "Item"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeList::Item method. Recupera un nodo en el índice dado en C++."
type: docs
weight: 400
url: /es/cpp/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item method


Recupera un nodo en el índice especificado.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | El índice basado en cero de la lista de nodos. |

### ReturnValue

El [XmlNode](../../xmlnode/) con el índice especificado en la colección. Si **index** es mayor o igual que el número de nodos en la lista, esto devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
