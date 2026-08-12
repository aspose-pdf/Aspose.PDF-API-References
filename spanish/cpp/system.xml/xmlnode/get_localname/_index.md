---
title: "System::Xml::XmlNode::get_LocalName método"
linktitle: "get_LocalName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNode::get_LocalName método. Devuelve el nombre local del nodo, cuando se sobrescribe en una clase derivada en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName method


Devuelve el nombre local del nodo, cuando se sobrescribe en una clase derivada.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### ReturnValue

El nombre del nodo sin el prefijo. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**.
## Observaciones



El nombre devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo: |||
|-|-|
| Tipo | Nombre |
| Atributo | El nombre local del atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | El nombre del tipo de documento. |
| Elemento | El nombre local del elemento. |
| Entity | El nombre de la entidad. |
| EntityReference | El nombre de la entidad referenciada. |
| Notation | El nombre de la notación. |
| ProcessingInstruction | El objetivo de la instrucción de procesamiento. |
| Text | #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| XmlDeclaration | #xml-declaration |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
