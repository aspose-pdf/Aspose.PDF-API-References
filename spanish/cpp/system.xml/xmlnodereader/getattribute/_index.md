---
title: "System::Xml::XmlNodeReader::GetAttribute método"
linktitle: "GetAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeReader::GetAttribute método. Devuelve el valor del atributo con el índice especificado en C++."
type: docs
weight: 2400
url: /es/cpp/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(int32_t) method


Devuelve el valor del atributo con el índice especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeIndex | int32_t | El índice del atributo. El índice comienza en cero. (El primer atributo tiene índice 0.) |

### ReturnValue

El valor del atributo especificado.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String) method


Devuelve el valor del atributo con el nombre especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String, String) method


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
