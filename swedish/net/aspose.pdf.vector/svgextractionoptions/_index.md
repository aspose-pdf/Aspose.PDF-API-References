---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions klass. Representerar en optionsklass för att extrahera vektorgrafik från pdf-dokumentets sida
type: docs
weight: 11240
url: /sv/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions klass

Representerar en optionsklass för att extrahera vektorgrafik från pdf-dokumentets sida.

```csharp
public class SvgExtractionOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Hämtar och sätter alternativet för att automatiskt gruppera delvägar till bilder. Detta alternativ utesluter alternativet [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Hämtar och sätter alternativet för att extrahera varje delväg från ett PDF-dokument till separata SVG-bilder. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Hämtar och sätter den begränsande rektangeln som definierar extraktionsområdet för SVG-extraktion. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Hämtar och sätter ett alternativ för styrkan av gruppering av delvägar till bilder. Gör att du kan konfigurera graden av gruppering av delvägar. Värdet sträcker sig från 0 till 1. Ett värde på 0 motsvarar att alternativet [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) är aktiverat. Ett värde på 1 kommer att skapa en enda bild för alla vektorvägar på sidan. Alternativet har en effekt när [`AutoGrouping`](./autogrouping/) är falskt. Standardvärdet är `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Hämtar eller sätter den minimi linjebredd som kommer att användas i den resulterande SVG:n. Om PDF:en använder en tunnare linjebredd kommer den att ersättas med denna bredd. Standardvärdet är 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Hämtar och sätter ett alternativ för att strikt kontrollera om delvägar ligger inom den angivna rektangeln i [`ExtractionAreaBound`](./extractionareabound/). Om det är inställt på falskt, kommer delvägar som inte helt ingår i [`ExtractionAreaBound`](./extractionareabound/) att extraheras. Standardvärdet är `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Hämtar och sätter en flagga som avgör om XForm som finns på sidor ska packas upp eller inte. XForm-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do-satser från sidinnehållet packas upp. Nästlade XForms packas inte upp. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Hämtar och sätter alternativet för att endast packa upp den XForm som motsvarar den angivna predikatet. |

### Se Även

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)