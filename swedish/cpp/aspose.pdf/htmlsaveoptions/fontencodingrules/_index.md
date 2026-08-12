---
title: "Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum"
linktitle: "FontEncodingRules"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum. Denna uppräkning definierar regler som finjusterar kodningslogiken i C++."
type: docs
weight: 5200
url: /sv/cpp/aspose.pdf/htmlsaveoptions/fontencodingrules/
---
## FontEncodingRules enum


Denna uppräkning definierar regler som finjusterar kodningslogiken.

```cpp
enum class FontEncodingRules : uint8_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Lämna kodningslogiken "as is" - i enlighet med PDF‑specifikationen. |
| DecreaseToUnicodePriorityLevel | 1 | ToUnicode är en speciell mekanism som hjälper till att avkoda inmatningskoder till Unicode‑symboler. Enligt specifikationen måste den användas som den första mekanismen för att få Unicode‑symboler för en specifik inmatningskod. Men vissa dokument har icke‑standardteckensnitt och för att konvertera dessa dokument korrekt kan det vara nödvändigt att minska ToUnicode‑prioriteten och använda andra mekanismer för att avkoda inmatningskoder. |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
