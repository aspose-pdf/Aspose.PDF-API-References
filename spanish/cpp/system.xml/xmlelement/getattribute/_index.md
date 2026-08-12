---
title: "Método System::Xml::XmlElement::GetAttribute"
linktitle: "GetAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlElement::GetAttribute. Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados en C++."
type: docs
weight: 1300
url: /es/cpp/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String, String) method


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo a obtener. |
| namespaceURI | String | El URI del espacio de nombres del atributo a obtener. |

### ReturnValue

El valor del atributo especificado. Se devuelve una cadena vacía si no se encuentra un atributo coincidente o si el atributo no tiene un valor especificado o predeterminado.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetAttribute(String) method


Devuelve el valor del atributo con el nombre especificado.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre del atributo a obtener. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. |

### ReturnValue

El valor del atributo especificado. Se devuelve una cadena vacía si no se encuentra un atributo coincidente o si el atributo no tiene un valor especificado o predeterminado.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
