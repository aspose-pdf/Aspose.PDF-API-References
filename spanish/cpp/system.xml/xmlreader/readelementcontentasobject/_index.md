---
title: "System::Xml::XmlReader::ReadElementContentAsObject método"
linktitle: "ReadElementContentAsObject"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadElementContentAsObject método. Lee el elemento actual y devuelve el contenido como un Object en C++."
type: docs
weight: 6200
url: /es/cpp/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Lee el elemento actual y devuelve el contenido como un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### ReturnValue

Un objeto empaquetado del tipo más apropiado. El valor de [XmlReader::get_ValueType](../get_valuetype/) determina el tipo apropiado. Si el contenido está tipado como una lista, este método devuelve una matriz de objetos empaquetados del tipo apropiado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAsObject(String, String) method


Comprueba que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del elemento. |
| namespaceURI | String | El URI del espacio de nombres del elemento. |

### ReturnValue

Un objeto empaquetado del tipo más apropiado. El valor de [XmlReader::get_ValueType](../get_valuetype/) determina el tipo apropiado. Si el contenido está tipado como una lista, este método devuelve una matriz de objetos empaquetados del tipo apropiado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
