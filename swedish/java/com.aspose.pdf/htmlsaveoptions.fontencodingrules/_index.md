---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna uppräkning definierar regler som finjusterar kodningslogiken"
type: docs
weight: 2050
url: /sv/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Denna uppräkning definierar regler som finjusterar kodningslogiken

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode är en speciell mekanism som hjälper till att avkoda inmatningskoder till unicode‑symboler. Enligt specifikationen måste den användas som den första av alla mekanismer för att få unicode‑symboler för en specifik inmatningskod. Men vissa dokument har icke‑standardteckensnitt och för att konvertera dessa dokument korrekt kan det vara nödvändigt att minska ToUnicode‑prioriteten och använda andra mekanismer för att avkoda inmatningskoder. |
| [Default](#Default) | Leave encoding logic "as is" - in accordance with PDF specification |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode är en speciell mekanism som hjälper till att avkoda inmatningskoder till unicode‑symboler. Enligt specifikationen måste den användas som den första av alla mekanismer för att få unicode‑symboler för en specifik inmatningskod. Men vissa dokument har icke‑standardteckensnitt och för att konvertera dessa dokument korrekt kan det vara nödvändigt att minska ToUnicode‑prioriteten och använda andra mekanismer för att avkoda inmatningskoder.

### Default {#Default}
```
public static final byte Default
```

Leave encoding logic "as is" - in accordance with PDF specification
