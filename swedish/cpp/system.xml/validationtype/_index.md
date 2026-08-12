---
title: "System::Xml::ValidationType enum"
linktitle: "ValidationType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::ValidationType enum. Anger vilken typ av validering som ska utföras i C++."
type: docs
weight: 5500
url: /sv/cpp/system.xml/validationtype/
---
## ValidationType enum


Anger vilken typ av validering som ska utföras.

```cpp
enum class ValidationType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Ingen validering utförs och inga valideringsfel kastas. Denna inställning skapar en XML 1.0‑kompatibel icke‑validerande parser. |
| Auto | 1 | Validerar om DTD‑ eller schemainformation hittas. |
| DTD | 2 | Validerar enligt DTD. |
| XDR | 3 | Validera enligt XML-Data Reduced (XDR)-scheman, inklusive inbäddade XDR-scheman. XDR‑scheman känns igen med namnrymdsprefixet **x-schema** eller värdet från [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Validera enligt XML [Schema](../../system.xml.schema/) definitionsspråk (XSD)-scheman, inklusive inbäddade XML‑scheman. XML‑scheman associeras med namnrymds‑URI:er antingen genom att använda attributet **schemaLocation** eller de tillhandahållna **Schemas**. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
