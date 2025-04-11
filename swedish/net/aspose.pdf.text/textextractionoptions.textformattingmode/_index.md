---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se TextDevice-klass
type: docs
weight: 10900
url: /sv/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode-uppräkning

Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se !:TextDevice-klass.

```csharp
public enum TextFormattingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Pure | `0` | Representera pdf-innehåll med en del formateringsrutiner. |
| Raw | `1` | Representera pdf-innehåll som det är, dvs utan formatering. |
| Flatten | `2` | Representera pdf-innehåll med positionering av textfragment efter deras koordinater. Det är i grunden liknande "Raw"-läget. Men medan "Raw" fokuserar på att bevara strukturen av textfragment (operatörer) i ett dokument, fokuserar "Flatten" på att hålla texten i den ordning den läses. |
| MemorySaving | `3` | Extraktion med minnesbesparing. Det är nästan samma som 'Raw'-läget men fungerar något snabbare och använder mindre minne. |

### Se Även

* klass [TextExtractionOptions](../textextractionoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* samling [Aspose.PDF](../../)