---
title: "System::Xml::XmlNamedNodeMap::RemoveNamedItem método"
linktitle: "RemoveNamedItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamedNodeMap::RemoveNamedItem método. Elimina un nodo con los valores coincidentes de XmlNode::get_LocalName y XmlNode::get_NamespaceURI en C++."
type: docs
weight: 900
url: /es/cpp/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String, String) method


Elimina un nodo con los valores coincidentes de [XmlNode::get_LocalName](../../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del nodo a eliminar. |
| namespaceURI | String | El URI del espacio de nombres del nodo a eliminar. |

### ReturnValue

El [XmlNode](../../xmlnode/) eliminado o **nullptr** si no se encontró un nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::RemoveNamedItem(String) method


Elimina el nodo del [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | String | El nombre calificado del nodo a eliminar. El nombre se compara con el valor de [XmlNode::get_Name](../../xmlnode/get_name/) del nodo coincidente. |

### ReturnValue

El [XmlNode](../../xmlnode/) eliminado de este [XmlNamedNodeMap](../) o **nullptr** si no se encontró un nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
