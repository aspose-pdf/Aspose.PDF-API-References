---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. Bestämmer åtgärden som kommer att göras efter att textfragmentet har ersatts med en kortare. Ingen - ingen åtgärd, ersatt text kan överlappa resten av raden; JusteraMellanslagBredd - försöker justera mellanslagen mellan ord för att hålla radens längd; HelaOrdBindning - försöker fördela ord mellan styckets rader för att hålla styckets rätta fält; SkiftRestenAvRaden - skiftar resten av raden enligt den förändrade längden på texten, längden på raden kan ändras; Standardvärdet är SkiftRestenAvRaden.
type: docs
weight: 11020
url: /sv/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Bestämmer åtgärden som kommer att göras efter att textfragmentet har ersatts med en kortare. Ingen - ingen åtgärd, ersatt text kan överlappa resten av raden; JusteraMellanslagBredd - försöker justera mellanslagen mellan ord för att hålla radens längd; HelaOrdBindning - försöker fördela ord mellan styckets rader för att hålla styckets rätta fält; SkiftRestenAvRaden - skiftar resten av raden enligt den förändrade längden på texten, längden på raden kan ändras; Standardvärdet är SkiftRestenAvRaden.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | `0` | Ingen åtgärd, ersatt text kan överlappa resten av raden |
| JusteraMellanslagBredd | `1` | Försöker justera mellanslagen mellan ord för att hålla radens längd |
| HelaOrdBindning | `2` | Försöker fördela ord mellan styckets rader för att hålla styckets rätta fält |
| ÄrFormFyllningsläge | `4` | Försöker sprida orden i det tillgängliga vita utrymmet med hjälp av styckets bredd. Om texten överflödar, kommer den att döljas. |
| SkiftRestenAvRaden | `8` | (Standard) Skiftar resten av raden enligt den förändrade längden på texten, längden på raden kan ändras |

### Se Även

* klass [TextReplaceOptions](../textreplaceoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)