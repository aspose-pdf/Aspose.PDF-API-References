---
title: "System::Xml::XmlReader::get_Value metod"
linktitle: "get_Value"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::get_Value metod. När den åsidosätts i en avledd klass, hämtar den textvärdet för den aktuella noden i C++."
type: docs
weight: 2400
url: /sv/cpp/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value method


När den åsidosätts i en avledd klass, hämtar den textvärdet för den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### ReturnValue

Det returnerade värdet beror på [XmlReader::get_NodeType](../get_nodetype/) värdet för noden.
## Anmärkningar



Följande tabell listar nodtyper som har ett värde att returnera. Alla andra nodtyper returnerar [String::Empty](../../../system/string/empty/). |||
|-|-|
| Nodtyp | Värde |
| Attribute | Värdet på attributet. |
| CDATA | Innehållet i CDATA-sektionen. |
| Comment | Innehållet i kommentaren. |
| DocumentType | Den interna delmängden. |
| ProcessingInstruction | Hela innehållet, exklusive målet. |
| SignificantWhitespace | Mellanslaget mellan markup i en blandad innehållsmodell. |
| Text | Innehållet i textnoden. |
| Whitespace | Mellanslaget mellan markup. |
| XmlDeclaration | Innehållet i deklarationen. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
