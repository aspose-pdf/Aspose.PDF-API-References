---
title: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum"
linktitle: "TextFormattingMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum. Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se TextDevice-klass i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.text/textextractionoptions/textformattingmode/
---
## TextFormattingMode enum


Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se klassen [TextDevice](../).

```cpp
enum class TextFormattingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Pure | 0 | Representera pdf-innehåll med lite formateringsrutiner. |
| Raw | 1 | Representera pdf-innehåll som det är, d.v.s. utan formatering. |
| Flatten | 2 | Representera pdf-innehåll med positionering av textfragment efter deras koordinater. Det är i princip liknande \"Raw\"-läget. Men medan \"Raw\" fokuserar på att bevara strukturen för textfragment (operatorer) i ett dokument, fokuserar \"Flatten\" på att hålla texten i den ordning den läses. |
| Minnesbesparing | 3 | Extraktion med minnesbesparing. Det är nästan samma som 'Raw'-läget men fungerar något snabbare och använder mindre minne. |

## Se även

* Class [TextExtractionOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
