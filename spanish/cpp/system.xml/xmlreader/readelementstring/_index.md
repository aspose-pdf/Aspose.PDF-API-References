---
title: "System::Xml::XmlReader::ReadElementString método"
linktitle: "ReadElementString"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::ReadElementString. Lee un elemento solo de texto. Sin embargo, se recomienda usar el método XmlReader::ReadElementContentAsString en su lugar, porque proporciona una forma más directa de manejar esta operación en C++."
type: docs
weight: 6400
url: /es/cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Lee un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

El texto contenido en el elemento que se leyó. Una cadena vacía si el elemento está vacío.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Comprueba que los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) del elemento encontrado coincidan con las cadenas proporcionadas antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | String | El nombre local a comprobar. |
| ns | String | El URI del espacio de nombres a comprobar. |

### ReturnValue

El texto contenido en el elemento que se leyó. Una cadena vacía si el elemento está vacío.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String) method


Comprueba que el valor [XmlReader::get_Name](../get_name/) del elemento encontrado coincida con la cadena proporcionada antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre a comprobar. |

### ReturnValue

El texto contenido en el elemento que se leyó. Una cadena vacía si el elemento está vacío.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
