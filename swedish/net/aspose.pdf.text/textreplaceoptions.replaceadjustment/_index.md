---
title: "Enum TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. Bestämmer åtgärden som kommer att utföras efter att en textfragment har ersatts med en kortare. None ingen åtgärd ersatt text kan överlappa resten av raden AdjustSpaceWidth försöker justera mellanslag mellan ord för att behålla radlängden WholeWordsHyphenation försöker fördela ord mellan stycke rader för att hålla styckets högra kant ShiftRestOfLine förskjuter resten av raden enligt förändrad textlängd radens längd kan ändras Standardvärdet är ShiftRestOfLine"
type: docs
weight: 11210
url: /sv/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Bestämmer åtgärden som ska utföras efter att ett textfragment har ersatts med ett kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan styckesrader för att hålla styckets högra kant; ShiftRestOfLine - förskjuter resten av raden enligt förändrad textlängd, radens längd kan ändras; Standardvärdet är ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen åtgärd, ersatt text kan överlappa resten av raden |
| AdjustSpaceWidth | `1` | Försöker justera mellanslag mellan ord för att behålla radlängden |
| WholeWordsHyphenation | `2` | Försöker fördela ord mellan styckesrader för att hålla styckets högra kant |
| IsFormFillingMode | `4` | Försöker sprida orden i det tillgängliga vita utrymmet med hjälp av styckets bredd. Om texten överflödar kommer den att döljas. |
| ShiftRestOfLine | `8` | (Standard) Förskjuter resten av raden enligt förändrad textlängd, radens längd kan ändras |

### Se även

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


