---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. Denna uppräkning definierar regler som justerar kodningslogik
type: docs
weight: 5620
url: /sv/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules uppräkning

Denna uppräkning definierar regler som justerar kodningslogik

```csharp
public enum FontEncodingRules : byte
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Lämna kodningslogik "som den är" - i enlighet med PDF-specifikationen |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode är en speciell mekanism som hjälper till att avkoda inmatningskoder till unicode-symboler. Enligt specifikationen måste den användas först av alla mekanismer för att få unicode-symboler för specifik inmatningskod. Men vissa dokument har icke-standardiserade typsnitt och för att konvertera dessa dokument korrekt kan det vara nödvändigt att minska ToUnicode-prioriteten och använda andra mekanismer för att avkoda inmatningskoder. |

### Se Även

* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrum [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)