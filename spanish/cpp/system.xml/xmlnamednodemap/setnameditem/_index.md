---
title: "System::Xml::XmlNamedNodeMap::SetNamedItem método"
linktitle: "SetNamedItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamedNodeMap::SetNamedItem método. Añade un XmlNode usando su valor XmlNode::get_Name en C++."
type: docs
weight: 1000
url: /es/cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Agrega un [XmlNode](../../xmlnode/) usando su valor de [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | Un [XmlNode](../../xmlnode/) para almacenar en el [XmlNamedNodeMap](../). Si un nodo con ese nombre ya está presente en el mapa, se reemplaza por el nuevo. |

### ReturnValue

Si el **node** reemplaza un nodo existente con el mismo nombre, se devuelve el nodo antiguo; de lo contrario, se devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
