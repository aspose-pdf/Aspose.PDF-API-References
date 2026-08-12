---
title: "System::Xml::XmlReader::GetAttribute method"
linktitle: "GetAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::GetAttribute method. Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado en C++."
type: docs
weight: 2800
url: /es/cpp/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(int32_t) method


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. El índice comienza en cero. (El primer atributo tiene índice 0.) |

### ReturnValue

El valor del atributo especificado. Este método no mueve el lector.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::GetAttribute(String) method


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el valor especificado de [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

El valor del atributo especificado. Si el atributo no se encuentra o el valor es [String::Empty](../../../system/string/empty/), se devuelve **nullptr**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::GetAttribute(String, String) method


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con los valores especificados de [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El valor del atributo especificado. Si el atributo no se encuentra o el valor es [String::Empty](../../../system/string/empty/), se devuelve **nullptr**. Este método no mueve el lector.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
