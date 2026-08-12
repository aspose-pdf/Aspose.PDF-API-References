---
title: "Método System::Xml::XmlReader::MoveToAttribute"
linktitle: "MoveToAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::MoveToAttribute. Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el índice especificado en C++."
type: docs
weight: 3200
url: /es/cpp/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(int32_t) method


Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el índice especificado.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. |

## Ver también

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String) method


Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String, String) method


Cuando se sobrescribe en una clase derivada, se desplaza al atributo con los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local del atributo. |
| ns | String | El URI del espacio de nombres del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
