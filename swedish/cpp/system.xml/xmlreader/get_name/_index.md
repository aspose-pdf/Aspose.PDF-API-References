---
title: "System::Xml::XmlReader::get_Name metod"
linktitle: "get_Name‑metod"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::get_Name metod. När den åsidosätts i en avledd klass hämtar den det kvalificerade namnet på den aktuella noden i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name method


När den åsidosätts i en avledd klass, hämtar den det kvalificerade namnet på den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### ReturnValue

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.
## Anmärkningar



Det returnerade namnet beror på värdet för [XmlReader::get_NodeType](../get_nodetype/) för noden. Följande nodtyper returnerar de angivna värdena. Alla andra nodtyper returnerar en tom sträng. |||
|-|-|
| Nodtyp | Namn |
| Attribute | Attributets namn. |
| DocumentType | Dokumenttypens namn. |
| Element | Taggnamnet. |
| EntityReference | Namnet på den refererade entiteten. |
| ProcessingInstruction | Målet för processinstruktionen. |
| XmlDeclaration | Den bokstavliga strängen xml. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
