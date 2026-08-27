---
title: "Enum PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Vissa document har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa document är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi från denna uppräkning har endast mening när flaggan OptimizeFileSize är satt."
type: docs
weight: 8540
url: /sv/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Vissa document har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa document är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi från denna uppräkning har endast mening när flaggan [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) är satt.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Denna strategi tar bort alla teckensnitt som har dubletter i document. Om document innehåller en grupp duplicerade teckensnitt embeddas endast ett teckensnitt från denna grupp i document. Alla andra teckensnitt från denna grupp tas bort från document, varje borttaget teckensnitt ersätts med den redan inbäddade motsvarigheten. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Denna strategi liknar RemoveDuplicatedFonts men den tar bort inte helt duplicerade teckensnitt utan teckensnitt som är liknande varandra och skiljer sig endast åt genom parametern "Widths". Denna parameter innehåller en uppsättning av vissa breddvärden för angivna tecken i teckensnittet. Varje breddvärde i denna "Widths"-uppsättning är inte den faktiska bredden på tecknet (glyph), den faktiska bredden för detta tecken är redan definierad i teckensnittets binära data. Breddvärdet i "Widths"-uppsättningen betyder den visuella bredden för detta tecken – den bredd som PDF‑visningsprogrammet måste använda när tecknet visas istället för den faktiska bredden som definierats i teckensnittet. Mer exakt säger specifikationen: Acrobat 5.0 och senare visare använder de glyph‑bredder som lagras i teckensnittsdictionaryn för att åsidosätta bredden på glyphs i själva teckensnittprogrammet, vilket förbättrar konsistensen i visning och utskrift av dokumentet. Denna strategi är mer effektiv än RemoveDuplicatedFonts men användning av den i vissa fall kan teoretiskt skada den visuella presentationen av det konverterade dokumentet. Detta fel kan uppstå eftersom deklarerade breddvärden för teckensnitt kan vara olika för samma tecken och i så fall kommer bredden på detta tecken att ändras till ett nytt värde efter teckensnittssubstitution – när det borttagna teckensnittet ersätts i dokumentet med ett redan inbäddat. Och om tecknets visuella bredd ändras kommer det att visas felaktigt och denna skillnad kan orsaka visuella fel såsom överlappande text eller andra problem. Men det beskrivna visuella felet är ett mycket sällsynt fall och denna strategi minskar dokumentets storlek mer effektivt. |
| SubsetFonts | `2` | Detta är den mest effektiva strategin för att minska dokumentets storlek. Den tar helt inbäddade teckensnittssamlingar och trimmar dem till endast de använda delmängderna. Det rekommenderas att använda denna strategi i kombination med RemoveDuplicatedFonts eller RemoveSimilarFontsWithDifferentWidths för att uppnå flera komprimeringseffekter på filstorleken. Att använda alla tre strategier samtidigt är meningslöst och strategin RemoveSimilarFontsWithDifferentWidths kommer inte att användas i detta fall. |

### Se även

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


