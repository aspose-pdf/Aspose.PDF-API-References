---
title: "System::Xml::XmlValidatingReader::get_Name metod"
linktitle: "get_Name‑metod"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::get_Name metod. Returnerar det kvalificerade namnet för den aktuella noden i C++."
type: docs
weight: 1700
url: /sv/cpp/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name method


Returnerar det kvalificerade namnet på den aktuella noden.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### ReturnValue

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.
## Anmärkningar



Det returnerade namnet beror på XmlValidatingReader::NodeType för noden. Följande nodtyper returnerar de listade värdena. Alla andra nodtyper returnerar en tom sträng. |||
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
