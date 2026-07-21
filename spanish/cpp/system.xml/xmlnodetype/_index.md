---
title: "System::Xml::XmlNodeType enumeración"
linktitle: "XmlNodeType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeType enumeración. Especifica el tipo de nodo en C++."
type: docs
weight: 6200
url: /es/cpp/system.xml/xmlnodetype/
---
## XmlNodeType enum


Especifica el tipo de nodo.

```cpp
enum class XmlNodeType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Esto es devuelto por el [XmlReader](../xmlreader/) si no se ha llamado al método **Read**. |
| Elemento | 1 | Un elemento (por ejemplo, **<item>**). |
| Atributo | 2 | Un atributo (por ejemplo, **id='123'**). |
| Text | 3 | El contenido de texto de un nodo. Un nodo [XmlNodeType::Text](./) no puede tener nodos hijos. Puede aparecer como nodo hijo de los nodos [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) y [XmlNodeType::EntityReference](./) nodos. |
| CDATA | 4 | Una sección CDATA (por ejemplo, **my escaped text**). |
| EntityReference | 5 | Una referencia a una entidad (por ejemplo, **&num;**). |
| Entity | 6 | Una declaración de entidad (por ejemplo, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Una instrucción de procesamiento (por ejemplo, **<?pi test?>**). |
| Comment | 8 | Un comentario (por ejemplo, ****). |
| Document | 9 | Un objeto de documento que, como la raíz del árbol del documento, brinda acceso a todo el documento XML. |
| DocumentType | 10 | La declaración de tipo de documento, indicada por la siguiente etiqueta (por ejemplo, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Un fragmento de documento. |
| Notation | 12 | Una notación en la declaración de tipo de documento (por ejemplo, **<!NOTATION...>**). |
| Whitespace | 13 | Espacio en blanco entre marcas. |
| SignificantWhitespace | 14 | Espacio en blanco entre marcas en un modelo de contenido mixto o espacio en blanco dentro del alcance **xml:space=\"preserve\"**. |
| EndElement | 15 | Una etiqueta de fin de elemento (por ejemplo, ****). |
| EndEntity | 16 | Devuelto cuando [XmlReader](../xmlreader/) llega al final del reemplazo de la entidad como resultado de una llamada a [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | La declaración XML (por ejemplo, **<?xml version='1.0'?>**). El nodo [XmlNodeType::XmlDeclaration](./) debe ser el primer nodo del documento. No puede tener hijos. Es un hijo del nodo [XmlNodeType::Document](./). Puede tener atributos que proporcionen información de versión y codificación. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
