---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Vissa dokument har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för borttagning av typsnitt. Denna enumeration deklarerar strategier som kan användas för att optimera användningen av typsnitt. Varje strategi från denna enumeration har mening endast när flaggan [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) är inställd.
type: docs
weight: 8400
url: /sv/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Vissa dokument har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för borttagning av typsnitt. Denna enumeration deklarerar strategier som kan användas för att optimera användningen av typsnitt. Varje strategi från denna enumeration har mening endast när flaggan [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) är inställd.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Denna strategi tar bort alla typsnitt som har dubbletter i dokumentet. Om dokumentet innehåller en grupp av dubbletttypsnitt så är endast ett typsnitt från denna grupp inbäddat i dokumentet. Alla andra typsnitt från denna grupp tas bort från dokumentet, varje borttaget typsnitt ersätts med den redan inbäddade motsvarigheten. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Denna strategi liknar RemoveDuplicatedFonts men den tar bort inte helt dubbletter utan typsnitt som är lika varandra och skiljer sig endast åt i parametern "Widths". Denna parameter innehåller en uppsättning av vissa bredder för specificerade symboler av typsnitt. Varje värde av bredd från denna "Widths"-uppsättning är inte den verkliga bredden av symbolen (glyph), den verkliga bredden för denna symbol är redan definierad i typsnittets binära data. Värdet av bredd från "Widths"-uppsättningen betyder visuell bredd för denna symbol - bredden som PDF-visningsprogrammet måste ställa in vid visning av symbolen istället för den verkliga bredden som definieras i typsnittet. Mer exakt säger specifikationen: Acrobat 5.0 och senare visare använder glyph-bredderna som lagras i typsnittets ordbok för att åsidosätta bredderna av glyphs i typsnittprogrammet självt, vilket förbättrar konsistensen i visningen och utskriften av dokumentet. Denna strategi är mer effektiv än RemoveDuplicatedFonts men användningen av denna strategi kan i vissa fall teoretiskt skada den visuella presentationen av det konverterade dokumentet. Denna defekt är möjlig på grund av att de deklarerade bredderna av typsnitt kan vara olika för samma symbol och i detta fall kommer bredden av denna symbol att ändras till en ny efter typsnittsersättning - när det borttagna typsnittet ersätts i dokumentet med det redan inbäddade. Och om symbolens visuella bredd ändras - kommer den att visas felaktigt och denna skillnad kan orsaka visuella defekter som textöverlappar eller andra problem. Men den beskrivna visuella defekten är ett mycket sällsynt fall och denna strategi minskar storleken på dokumentet mer effektivt. |
| SubsetFonts | `2` | Detta är den mest effektiva strategin för att minska dokumentets storlek. Den tar helt inbäddade typsnittssatser och trimma dem ner till endast de delmängder som används. Det rekommenderas att använda denna strategi i kombination med RemoveDuplicatedFonts eller RemoveSimilarFontsWithDifferentWidths för att få en multipel kompressionseffekt för filstorleken. Användningen av alla tre strategier samtidigt har ingen mening och strategin RemoveSimilarFontsWithDifferentWidths kommer inte att användas i detta fall. |

### Se Även

* klass [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)