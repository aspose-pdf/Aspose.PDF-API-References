---
title: "System::Xml::XmlReader::IsStartElement método"
linktitle: "IsStartElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::IsStartElement método. Llama a XmlReader::MoveToContent y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío en C++."
type: docs
weight: 3000
url: /es/cpp/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### ReturnValue

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## Ver también

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String, String) method


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) del elemento encontrado coinciden con las cadenas dadas.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | String | La cadena para comparar con el valor **LocalName** del elemento encontrado. |
| ns | String | La cadena para comparar con el valor **NamespaceURI** del elemento encontrado. |

### ReturnValue

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String) method


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si el valor [XmlReader::get_Name](../get_name/) del elemento encontrado coincide con el argumento proporcionado.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | La cadena comparada con el valor **Name** del elemento encontrado. |

### ReturnValue

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
