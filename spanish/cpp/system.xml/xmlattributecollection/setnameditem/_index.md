---
title: "System::Xml::XmlAttributeCollection::SetNamedItem método"
linktitle: "SetNamedItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttributeCollection::SetNamedItem método. Añade un XmlNode usando su resultado XmlNode::get_Name en C++."
type: docs
weight: 1000
url: /es/cpp/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem method


Añade un [XmlNode](../../xmlnode/) usando su resultado [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | SharedPtr\<XmlNode\> | Un nodo de atributo para almacenar en esta colección. El nodo será accesible posteriormente mediante el nombre del nodo. Si ya existe un nodo con ese nombre en la colección, se reemplaza por el nuevo; de lo contrario, el nodo se agrega al final de la colección. |

### ReturnValue

Si el **node** reemplaza a un nodo existente con el mismo nombre, se devuelve el nodo antiguo; de lo contrario, se devuelve el nodo añadido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
