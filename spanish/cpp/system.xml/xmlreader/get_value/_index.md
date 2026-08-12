---
title: "Método System::Xml::XmlReader::get_Value"
linktitle: "get_Value"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::get_Value. Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual en C++."
type: docs
weight: 2400
url: /es/cpp/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value method


Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### ReturnValue

El valor devuelto depende del valor [XmlReader::get_NodeType](../get_nodetype/) del nodo.
## Observaciones



La tabla siguiente enumera los tipos de nodo que tienen un valor para devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). |||
|-|-|
| Tipo de nodo | Valor |
| Atributo | El valor del atributo. |
| CDATA | El contenido de la sección CDATA. |
| Comment | El contenido del comentario. |
| DocumentType | El subconjunto interno. |
| ProcessingInstruction | Todo el contenido, excluyendo el objetivo. |
| SignificantWhitespace | El espacio en blanco entre marcas en un modelo de contenido mixto. |
| Text | El contenido del nodo de texto. |
| Whitespace | El espacio en blanco entre marcas. |
| XmlDeclaration | El contenido de la declaración. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
