---
title: "System::Xml::XmlElement::GetElementsByTagName método"
linktitle: "GetElementsByTagName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement::GetElementsByTagName método. Devuelve un XmlNodeList que contiene una lista de todos los elementos descendientes que coinciden con los valores especificados de XmlElement::get_LocalName y XmlElement::get_NamespaceURI en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String, String) method


Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con los valores especificados de [XmlElement::get_LocalName](../get_localname/) y [XmlElement::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local a coincidir. El asterisco (*) es un valor especial que coincide con todas las etiquetas. |
| namespaceURI | String | El URI del espacio de nombres a coincidir. |

### ReturnValue

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. La lista está vacía si no hay nodos coincidentes.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetElementsByTagName(String) method


Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlElement::get_Name](../get_name/) especificado.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | La etiqueta de nombre a coincidir. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. El asterisco (*) es un valor especial que coincide con todas las etiquetas. |

### ReturnValue

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. La lista está vacía si no hay nodos coincidentes.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
