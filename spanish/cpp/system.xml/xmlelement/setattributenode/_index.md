---
title: "System::Xml::XmlElement::SetAttributeNode método"
linktitle: "SetAttributeNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement::SetAttributeNode método. Añade el XmlAttribute especificado en C++."
type: docs
weight: 2700
url: /es/cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Añade el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newAttr | SharedPtr\<XmlAttribute\> | El nodo [XmlAttribute](../../xmlattribute/) que se añadirá a la colección de atributos de este elemento. |

### ReturnValue

Si el atributo reemplaza a un atributo existente con el mismo nombre, se devuelve el antiguo [XmlAttribute](../../xmlattribute/); de lo contrario, se devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::SetAttributeNode(String, String) method


Añade el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) a añadir.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
