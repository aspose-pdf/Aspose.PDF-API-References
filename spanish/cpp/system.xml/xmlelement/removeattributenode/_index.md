---
title: "System::Xml::XmlElement::RemoveAttributeNode método"
linktitle: "RemoveAttributeNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement::RemoveAttributeNode método. Elimina el XmlAttribute especificado en C++."
type: docs
weight: 2100
url: /es/cpp/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Elimina el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldAttr | SharedPtr\<XmlAttribute\> | El nodo [XmlAttribute](../../xmlattribute/) a eliminar. Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) eliminado o **nullptr** si **oldAttr** no es un nodo de atributo del [XmlElement](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::RemoveAttributeNode(String, String) method


Elimina el [XmlAttribute](../../xmlattribute/) especificado por el nombre local y el URI del espacio de nombres. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) eliminado o **nullptr** si el [XmlElement](../) no tiene un nodo de atributo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
