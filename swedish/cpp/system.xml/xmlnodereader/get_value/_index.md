---
title: "System::Xml::XmlNodeReader::get_Value metod"
linktitle: "get_Value"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::get_Value metod. Returnerar textvärdet för den aktuella noden i C++."
type: docs
weight: 2100
url: /sv/cpp/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value method


Returnerar textvärdet för den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### ReturnValue

Det returnerade värdet beror på [XmlNodeReader::get_NodeType](../get_nodetype/) för noden.
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
