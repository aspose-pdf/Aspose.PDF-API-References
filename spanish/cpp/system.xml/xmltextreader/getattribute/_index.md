---
title: "Método System::Xml::XmlTextReader::GetAttribute"
linktitle: "GetAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlTextReader::GetAttribute. Devuelve el valor del atributo con el índice especificado en C++."
type: docs
weight: 3300
url: /es/cpp/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(int32_t) method


Devuelve el valor del atributo con el índice especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. El índice comienza en cero. (El primer atributo tiene índice 0.) |

### ReturnValue

El valor del atributo especificado.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::GetAttribute(String, String) method


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**. Este método no mueve al lector.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::GetAttribute(String) method


Devuelve el valor del atributo con el nombre especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del atributo. |

### ReturnValue

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
