---
title: "System::Xml::XmlElement::GetAttributeNode método"
linktitle: "GetAttributeNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement::GetAttributeNode método. Devuelve el XmlAttribute con el nombre local y el URI del espacio de nombres especificados en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String, String) method


Devuelve el [XmlAttribute](../../xmlattribute/) con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) especificado o **nullptr** si no se encontró un atributo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetAttributeNode(String) method


Devuelve el [XmlAttribute](../../xmlattribute/) con el nombre especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre del atributo a obtener. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) especificado o **nullptr** si no se encontró un atributo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
