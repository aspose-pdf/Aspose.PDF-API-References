---
title: "System::Xml::XmlTextReader::get_Value método"
linktitle: "get_Value"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::get_Value método. Devuelve el valor de texto del nodo actual en C++."
type: docs
weight: 2900
url: /es/cpp/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value method


Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### ReturnValue

El valor devuelto depende del valor [XmlTextReader::get_NodeType](../get_nodetype/) del nodo.
## Observaciones



La tabla siguiente enumera los tipos de nodo que tienen un valor para devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). |||
|-|-|
| Tipo de nodo | Valor |
| Atributo | El valor del atributo. |
| CDATA | El contenido de la sección CDATA. |
| Comment | El contenido del comentario. |
| DocumentType | El subconjunto interno. |
| ProcessingInstruction | Todo el contenido, excluyendo el objetivo. |
| SignificantWhitespace | El espacio en blanco dentro de un ámbito xml:space='preserve'. |
| Text | El contenido del nodo de texto. |
| Whitespace | El espacio en blanco entre marcas. |
| XmlDeclaration | El contenido de la declaración. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
