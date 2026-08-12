---
title: "System::Xml::Schema::XmlSchemaContentProcessing enum"
linktitle: "XmlSchemaContentProcessing"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaContentProcessing enum. Tillhandahåller information om valideringsläget för any- och anyAttribute‑elementers ersättningar i C++."
type: docs
weight: 7300
url: /sv/cpp/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum


Tillhandahåller information om valideringsläget för ersättningar av **any**- och **anyAttribute**-element.

```cpp
enum class XmlSchemaContentProcessing
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Dokumentobjekt valideras inte. |
| Skip | 1 | Dokumentobjekt måste bestå av välformad XML och valideras inte av schemat. |
| Lax | 2 | Om det associerade schemat hittas kommer dokumentobjekten att valideras. Inga fel kommer att kastas annars. |
| Strict | 3 | Schemaprocessorn måste hitta ett schema som är associerat med den angivna namnrymden för att validera dokumentobjekten. |

## Se även

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
