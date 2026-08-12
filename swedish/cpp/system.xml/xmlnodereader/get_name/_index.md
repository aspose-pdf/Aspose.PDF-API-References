---
title: "System::Xml::XmlNodeReader::get_Name-metod"
linktitle: "get_Name‑metod"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::get_Name-metod. Returnerar det kvalificerade namnet på den aktuella noden i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name method


Returnerar det kvalificerade namnet på den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### ReturnValue

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.
## Anmärkningar



Namnet som returneras beror på värdet för [XmlNodeReader::get_NodeType](../get_nodetype/) för noden. Följande nodtyper returnerar de listade värdena. Alla andra nodtyper returnerar en tom sträng. |||
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
