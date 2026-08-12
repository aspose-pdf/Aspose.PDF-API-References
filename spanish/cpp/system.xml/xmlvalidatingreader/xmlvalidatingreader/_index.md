---
title: "Constructor System::Xml::XmlValidatingReader::XmlValidatingReader"
linktitle: "XmlValidatingReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlValidatingReader::XmlValidatingReader constructor. Inicializa una nueva instancia de la clase XmlValidatingReader con los valores especificados en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Inicializa una nueva instancia de la clase [XmlValidatingReader](../) con los valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | El flujo que contiene el fragmento XML a analizar. |
| fragType | XmlNodeType | El [XmlNodeType](../../xmlnodetype/) del fragmento XML. Esto determina lo que el fragmento puede contener (ver tabla a continuación). |
| context | const SharedPtr\<XmlParserContext\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar el fragmento XML. Esto incluye la [XmlNameTable](../../xmlnametable/) a usar, la codificación, el alcance del espacio de nombres, el **xml:lang** actual y el alcance del **xml:space**. |
## Observaciones



La tabla siguiente enumera los valores válidos para **fragType** y cómo el lector analiza cada uno de los diferentes tipos de nodo. |||
|-|-|
| XmlNodeType | El fragmento puede contener |
| Elemento | Cualquier contenido de elemento válido (por ejemplo, cualquier combinación de elementos, comentarios, instrucciones de procesamiento, cdata, texto y referencias de entidad). |
| Atributo | El valor de un atributo (la parte dentro de las comillas). |
| Document | El contenido de un documento XML completo; esto impone reglas a nivel de documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Inicializa una nueva instancia de la clase [XmlValidatingReader](../) que valida el contenido devuelto por el [XmlReader](../../xmlreader/) proporcionado.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | El [XmlReader](../../xmlreader/) del cual leer durante la validación. La implementación actual solo admite [XmlTextReader](../../xmltextreader/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Inicializa una nueva instancia de la clase [XmlValidatingReader](../) con los valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const String\& | La cadena que contiene el fragmento XML a analizar. |
| fragType | XmlNodeType | El [XmlNodeType](../../xmlnodetype/) del fragmento XML. Esto también determina lo que la cadena del fragmento puede contener (ver tabla a continuación). |
| context | const SharedPtr\<XmlParserContext\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar el fragmento XML. Esto incluye la [NameTable](../../nametable/) a usar, la codificación, el alcance del espacio de nombres, el **xml:lang** actual y el alcance del **xml:space**. |
## Observaciones



La tabla siguiente enumera los valores válidos para **fragType** y cómo el lector analiza cada uno de los diferentes tipos de nodo. |||
|-|-|
| XmlNodeType | El fragmento puede contener |
| Elemento | Cualquier contenido de elemento válido (por ejemplo, cualquier combinación de elementos, comentarios, instrucciones de procesamiento, cdata, texto y referencias de entidad). |
| Atributo | El valor de un atributo (la parte dentro de las comillas). |
| Document | El contenido de un documento XML completo; esto impone reglas a nivel de documento. |

## Ver también

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
