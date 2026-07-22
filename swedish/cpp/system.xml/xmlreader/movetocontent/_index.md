---
title: "System::Xml::XmlReader::MoveToContent‑metod"
linktitle: "MoveToContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::MoveToContent‑metod. Kontrollerar om den aktuella noden är en innehållsnod (text utan blanksteg, CDATA, Element, EndElement, EntityReference eller EndEntity). Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller slutet på filen. Den hoppar över noder av följande typer: ProcessingInstruction, DocumentType, Comment, Whitespace eller SignificantWhitespace i C++."
type: docs
weight: 3300
url: /sv/cpp/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent method


Kontrollerar om den aktuella noden är en innehållsnod (icke‑blankstegstext, **CDATA**, **Element**, **EndElement**, **EntityReference** eller **EndEntity**). Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller filslut. Den hoppar över noder av följande typer: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** eller **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### ReturnValue

Värdet [XmlReader::get_NodeType](../get_nodetype/) för den aktuella noden som hittas av metoden eller [XmlNodeType::None](../../xmlnodetype/) om läsaren har nått slutet på inmatningsströmmen.

## Se även

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
