---
title: "Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy‑enum"
linktitle: "RemoveFontsStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy‑enum. Vissa dokument får stor storlek efter konvertering till PDF/A‑format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi i denna uppräkning har bara mening när flaggan OptimizeFileSize är satt i C++."
type: docs
weight: 4300
url: /sv/cpp/aspose.pdf/pdfformatconversionoptions/removefontsstrategy/
---
## RemoveFontsStrategy enum


Vissa dokument har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi i denna uppräkning har mening endast när flaggan [OptimizeFileSize](../) är satt.

```cpp
enum class RemoveFontsStrategy : uint8_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RemoveDuplicatedFonts | 4 | Denna strategi tar bort alla teckensnitt som har dubletter i dokumentet. Om dokumentet innehåller en grupp duplicerade teckensnitt embeddas endast ett teckensnitt från gruppen i dokumentet. Alla andra teckensnitt i gruppen tas bort från dokumentet, och varje borttaget teckensnitt ersätts med den redan inbäddade motsvarigheten. |
| RemoveSimilarFontsWithDifferentWidths | 1 | Denna strategi liknar [RemoveDuplicatedFonts](./) men den tar bort inte helt duplicerade teckensnitt utan teckensnitt som är liknande varandra och skiljer sig endast åt med parametern "Widths". Denna parameter innehåller en uppsättning av vissa breddvärden för specificerade tecken i teckensnittet. Varje breddvärde i denna "Widths"‑uppsättning är inte den faktiska bredden för symbolen (glyph), den verkliga bredden för denna symbol är redan definierad i teckensnittets binära data. Breddvärdet från "Widths"‑uppsättningen betyder den visuella bredden för denna symbol – den bredd som PDF‑visningsprogrammet måste använda vid visning av symbolen istället för den faktiska bredden som definierats i teckensnittet. Mer exakt säger specifikationen: Acrobat 5.0 och senare visare använder glyfbreddarna som lagras i teckensnittets katalog för att åsidosätta bredden på glyfer i själva teckensnittet, vilket förbättrar konsistensen i visning och utskrift av dokumentet. Denna strategi är mer effektiv än [RemoveDuplicatedFonts](./) men användning av den i vissa fall kan teoretiskt skada den visuella presentationen av det konverterade dokumentet. Detta fel kan uppstå eftersom de deklarerade breddarna för teckensnitt kan vara olika för samma symbol och i så fall kommer symbolens bredd att ändras till en ny efter teckensnittssubstitution – när ett borttaget teckensnitt ersätts i dokumentet med ett redan inbäddat. Och om symbolens visuella bredd ändras – kommer den att visas felaktigt och denna skillnad kan orsaka visuella fel som överlappande text eller andra problem. Men det beskrivna visuella felet är ett mycket sällsynt fall och denna strategi minskar dokumentets storlek mer effektivt. |
| SubsetFonts | 2 | Detta är den mest effektiva strategin för att minska dokumentets storlek. Den tar helt inbäddade teckensnittssamlingar och beskär dem till endast de använda delmängderna. Det rekommenderas att använda denna strategi i kombination med [RemoveDuplicatedFonts](./) eller [RemoveSimilarFontsWithDifferentWidths](./) för att uppnå flera komprimeringseffekter på filstorleken. Att använda alla tre strategierna samtidigt är meningslöst och strategin [RemoveSimilarFontsWithDifferentWidths](./) kommer inte att användas i detta fall. |

## Se även

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
