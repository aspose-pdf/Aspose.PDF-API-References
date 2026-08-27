---
title: "Enum HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. Denna uppräkning definierar regler som finjusterar kodningslogiken"
type: docs
weight: 5750
url: /sv/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Denna uppräkning definierar regler som finjusterar kodningslogiken

```csharp
public enum FontEncodingRules : byte
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Lämna kodningslogiken "som den är" - i enlighet med PDF-specifikationen |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode är en speciell mekanism som hjälper till att avkoda inmatningskoder till Unicode‑symboler. Enligt specifikationen måste den användas som den främsta mekanismen för att få Unicode‑symboler för en specifik inmatningskod. Men vissa dokument har icke‑standardteckensnitt och för att konvertera dessa dokument korrekt kan det vara nödvändigt att minska ToUnicode‑prioriteten och använda andra mekanismer för att avkoda inmatningskoder. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


