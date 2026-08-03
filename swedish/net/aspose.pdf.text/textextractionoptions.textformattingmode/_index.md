---
title: "Enum TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode-enum. Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se TextDevice-klass."
type: docs
weight: 11080
url: /sv/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

Definierar olika lägen som kan användas när man konverterar pdf-dokument till text. Se !:TextDevice klass.

```csharp
public enum TextFormattingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Pure | `0` | Representerar pdf-innehåll med lite formateringsrutiner. |
| Raw | `1` | Representerar pdf-innehåll som det är, d.v.s. utan formatering. |
| Flatten | `2` | Representerar pdf-innehåll med positionering av textfragment efter deras koordinater. Det är i princip liknande "Raw"-läget. Men medan "Raw" fokuserar på att bevara strukturen för textfragment (operatorer) i ett dokument, fokuserar "Flatten" på att hålla texten i den ordning den läses. |
| MemorySaving | `3` | Extraktion med minnessparande. Det är nästan samma som 'Raw'-läget men fungerar något snabbare och använder mindre minne. |

### Se även

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


