---
title: "System::Xml::XmlNode::get_Name método"
linktitle: "get_Name"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNode::get_Name método. Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name method


Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### ReturnValue

El nombre calificado del nodo.
## Observaciones



El nombre devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo: |||
|-|-|
| Tipo | Nombre |
| Atributo | El nombre calificado del atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | El nombre del tipo de documento. |
| Elemento | El nombre calificado del elemento. |
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
