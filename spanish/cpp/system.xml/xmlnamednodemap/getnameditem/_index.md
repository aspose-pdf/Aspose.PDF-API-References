---
title: "System::Xml::XmlNamedNodeMap::GetNamedItem método"
linktitle: "GetNamedItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamedNodeMap::GetNamedItem método. Recupera un nodo con los valores coincidentes de XmlNode::get_LocalName y XmlNode::get_NamespaceURI en C++."
type: docs
weight: 700
url: /es/cpp/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String, String) method


Recupera un nodo con los valores coincidentes de [XmlNode::get_LocalName](../../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del nodo a recuperar. |
| namespaceURI | String | El Identificador Uniforme de Recursos (URI) del espacio de nombres del nodo a recuperar. |

### ReturnValue

Un [XmlNode](../../xmlnode/) con el nombre local y el URI del espacio de nombres coincidentes o **nullptr** si no se encontró un nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::GetNamedItem(String) method


Recupera un [XmlNode](../../xmlnode/) especificado por nombre.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | String | El nombre calificado del nodo a recuperar. Se compara con el valor de [XmlNode::get_Name](../../xmlnode/get_name/) del nodo coincidente. |

### ReturnValue

Un [XmlNode](../../xmlnode/) con el nombre especificado o **nullptr** si no se encuentra un nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
