---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Vissa dokument har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning."
type: docs
weight: 3760
url: /sv/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Vissa dokument får stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi i denna uppräkning är meningsfull endast när flaggan {@code OptimizeFileSize} är satt.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Denna strategi tar bort alla teckensnitt som har dubletter i dokumentet. Om dokumentet innehåller en grupp duplicerade teckensnitt, bäddas endast ett teckensnitt från denna grupp in i dokumentet. Alla andra teckensnitt från denna grupp tas bort från dokumentet, varje borttaget teckensnitt ersätts med den redan inbäddade motsvarigheten. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Denna strategi liknar {@code RemoveDuplicatedFonts} men den tar bort inte helt duplicerade teckensnitt utan teckensnitt som är liknande varandra och skiljer sig endast på parametern "Widths". Denna parameter innehåller en uppsättning av vissa breddvärden för angivna symboler i teckensnittet. Varje breddvärde från denna "Widths"-uppsättning är inte den faktiska bredden på symbolen (glyph), den faktiska bredden för denna symbol är redan definierad i teckensnittets binära data. Breddvärdet från "Widths"-uppsättningen betyder den visuella bredden för denna symbol – den bredd som PDF‑visningsprogrammet måste använda vid visning av symbolen istället för den faktiska bredden som definieras i teckensnittet. Mer exakt säger specifikationen: Acrobat 5.0 och senare visare använder de glyfbreddar som lagras i teckensnittets katalog för att åsidosätta bredden på glyfer i själva teckensnittet, vilket förbättrar konsistensen i visning och utskrift av dokumentet. Denna strategi är mer effektiv än {@code RemoveDuplicatedFonts} men användning av denna strategi kan i vissa fall teoretiskt skada den visuella presentationen av det konverterade dokumentet. Detta fel är möjligt eftersom de deklarerade breddarna för teckensnitt kan vara olika för samma symbol, och i så fall kommer bredden för denna symbol att ändras till en ny efter teckensnittssubstitution – när det borttagna teckensnittet ersätts i dokumentet med ett redan inbäddat. Och om symbolens visuella bredd ändras – visas den felaktigt och denna skillnad kan orsaka visuella fel såsom överlappande text eller andra problem. Men det beskrivna visuella felet är ett mycket sällsynt fall och denna strategi minskar dokumentets storlek mer effektivt. |
| [SubsetFonts](#SubsetFonts) | Detta är den mest effektiva strategin för att minska dokumentets storlek. Den tar helt inbäddade teckensnittssamlingar och trimmar dem till endast de använda delmängderna. Det rekommenderas att använda denna strategi i kombination med {@code RemoveDuplicatedFonts} eller {@code RemoveSimilarFontsWithDifferentWidths} för att uppnå flera komprimeringseffekter på filstorleken. Att använda alla tre strategierna samtidigt är meningslöst och strategin {@code RemoveSimilarFontsWithDifferentWidths} kommer inte att användas i detta fall. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Denna strategi tar bort alla teckensnitt som har dubletter i dokumentet. Om dokumentet innehåller en grupp duplicerade teckensnitt, bäddas endast ett teckensnitt från denna grupp in i dokumentet. Alla andra teckensnitt från denna grupp tas bort från dokumentet, varje borttaget teckensnitt ersätts med den redan inbäddade motsvarigheten.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Denna strategi liknar {@code RemoveDuplicatedFonts} men den tar bort inte helt duplicerade teckensnitt utan teckensnitt som är liknande varandra och skiljer sig endast på parametern "Widths". Denna parameter innehåller en uppsättning av vissa breddvärden för angivna symboler i teckensnittet. Varje breddvärde från denna "Widths"-uppsättning är inte den faktiska bredden på symbolen (glyph), den faktiska bredden för denna symbol är redan definierad i teckensnittets binära data. Breddvärdet från "Widths"-uppsättningen betyder den visuella bredden för denna symbol – den bredd som PDF‑visningsprogrammet måste använda vid visning av symbolen istället för den faktiska bredden som definieras i teckensnittet. Mer exakt säger specifikationen: Acrobat 5.0 och senare visare använder de glyfbreddar som lagras i teckensnittets katalog för att åsidosätta bredden på glyfer i själva teckensnittet, vilket förbättrar konsistensen i visning och utskrift av dokumentet. Denna strategi är mer effektiv än {@code RemoveDuplicatedFonts} men användning av denna strategi kan i vissa fall teoretiskt skada den visuella presentationen av det konverterade dokumentet. Detta fel är möjligt eftersom de deklarerade breddarna för teckensnitt kan vara olika för samma symbol, och i så fall kommer bredden för denna symbol att ändras till en ny efter teckensnittssubstitution – när det borttagna teckensnittet ersätts i dokumentet med ett redan inbäddat. Och om symbolens visuella bredd ändras – visas den felaktigt och denna skillnad kan orsaka visuella fel såsom överlappande text eller andra problem. Men det beskrivna visuella felet är ett mycket sällsynt fall och denna strategi minskar dokumentets storlek mer effektivt.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Detta är den mest effektiva strategin för att minska dokumentets storlek. Den tar helt inbäddade teckensnittssamlingar och trimmar dem till endast de använda delmängderna. Det rekommenderas att använda denna strategi i kombination med {@code RemoveDuplicatedFonts} eller {@code RemoveSimilarFontsWithDifferentWidths} för att uppnå flera komprimeringseffekter på filstorleken. Att använda alla tre strategierna samtidigt är meningslöst och strategin {@code RemoveSimilarFontsWithDifferentWidths} kommer inte att användas i detta fall.
