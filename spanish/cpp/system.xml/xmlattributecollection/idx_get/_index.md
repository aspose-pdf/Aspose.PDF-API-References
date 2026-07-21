---
title: "Método idx_get de System::Xml::XmlAttributeCollection"
linktitle: "idx_get"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttributeCollection::idx_get método. Devuelve el atributo con el nombre local y el Identificador Uniforme de Recursos (URI) de espacio de nombres especificados en C++."
type: docs
weight: 300
url: /es/cpp/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(const String\&, const String\&) method


Devuelve el atributo con el nombre local y el URI (Identificador Uniforme de Recursos) del espacio de nombres especificados.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del atributo. |
| namespaceURI | const String\& | El URI del espacio de nombres del atributo. |

### ReturnValue

El atributo con el nombre local y el URI de espacio de nombres especificados. Si el atributo no existe, este método devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(const String\&) method


Devuelve el atributo con el nombre especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const String\& | El nombre calificado del atributo. |

### ReturnValue

El atributo con el nombre especificado. Si el atributo no existe, este método devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(int32_t) method


Devuelve el atributo con el índice especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. |

### ReturnValue

El atributo en el índice especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
