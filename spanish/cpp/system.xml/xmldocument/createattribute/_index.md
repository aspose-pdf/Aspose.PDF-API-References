---
title: "System::Xml::XmlDocument::CreateAttribute método"
linktitle: "CreateAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDocument::CreateAttribute método. Crea un XmlAttribute con el nombre especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con el nombre especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | El nombre calificado del atributo. Si el nombre contiene dos puntos, el valor de [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refleja la parte del nombre que precede al primer dos puntos y el valor de [XmlDocument::get_LocalName](../get_localname/) refleja la parte del nombre que sigue al primer dos puntos. El [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) permanece vacío a menos que el prefijo sea un prefijo incorporado reconocido como **xmlns**. En este caso, get_NamespaceURI tiene un valor de [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ReturnValue

El nuevo [XmlAttribute](../../xmlattribute/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con el [XmlNode::get_Prefix](../../xmlnode/get_prefix/) especificado, el [XmlDocument::get_LocalName](../get_localname/) especificado y el [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const String\& | El prefijo del atributo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| localName | const String\& | El nombre local del atributo. |
| namespaceURI | const String\& | El URI del espacio de nombres del atributo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. Si **prefix** es **xmlns**, entonces este parámetro debe ser [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) de lo contrario se lanza una excepción. |

### ReturnValue

El nuevo [XmlAttribute](../../xmlattribute/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con el nombre calificado especificado y el [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| qualifiedName | const String\& | El nombre calificado del atributo. Si el nombre contiene dos puntos, el valor de [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflejará la parte del nombre que precede al dos puntos y el valor de [XmlDocument::get_LocalName](../get_localname/) reflejará la parte del nombre que sigue al dos puntos. |
| namespaceURI | const String\& | El namespaceURI del atributo. Si el nombre calificado incluye un prefijo **xmlns**, entonces este parámetro debe ser [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ReturnValue

El nuevo [XmlAttribute](../../xmlattribute/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
