---
title: "System::Xml::XmlNode::get_Name‑metod"
linktitle: "get_Name‑metod"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::get_Name‑metod. Returnerar det kvalificerade namnet på noden när den åsidosätts i en avledd klass i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name method


Returnerar det kvalificerade namnet på noden när den åsidosätts i en avledd klass.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### ReturnValue

Det kvalificerade namnet på noden.
## Anmärkningar



Det returnerade namnet beror på [XmlNode::get_NodeType](../get_nodetype/) för noden: |||
|-|-|
| Typ | Namn |
| Attribute | Det kvalificerade namnet på attributet. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Dokumenttypens namn. |
| Element | Det kvalificerade namnet på elementet. |
| Entity | Entitetens namn. |
| EntityReference | Namnet på den refererade entiteten. |
| Notation | Notationens namn. |
| ProcessingInstruction | Målet för processinstruktionen. |
| Text | #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| XmlDeclaration | #xml-declaration |

## Se även

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
