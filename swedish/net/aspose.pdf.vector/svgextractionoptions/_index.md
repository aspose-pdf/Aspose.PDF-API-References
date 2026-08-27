---
title: "Klass SvgExtractionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Vector.SvgExtractionOptions-klass. Representerar en alternativklass för att extrahera vektorgrafik från pdf Document-sidan"
type: docs
weight: 11430
url: /sv/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Representerar en alternativklass för extrahering av vektorgrafik från pdf-dokumentets sida.

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
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ exkluderar [`GroupStrength`](./groupstrength/)-alternativet. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Hämtar och anger alternativet för att extrahera varje subpath från ett PDF Document till separata SVG‑bilder. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Hämtar och anger den begränsande Rectangle som definierar extraheringsområdet för SVG‑extraktion. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Hämtar och anger ett alternativ för styrkan i gruppering av subpaths till bilder. Gör det möjligt att konfigurera graden av gruppering av subpaths. Värdet varierar från 0 till 1. Ett värde på 0 motsvarar att [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/)-alternativet är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när [`AutoGrouping`](./autogrouping/) är falskt. Standardvärdet är `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Hämtar eller anger den minsta streckbredden som kommer att användas i den resulterande SVG:n. Om PDF använder en tunnare streckbredd ersätts den med denna bredd. Standardvärdet är 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Hämtar och anger ett alternativ för att strikt kontrollera om subpaths ligger inom den angivna Rectangle i [`ExtractionAreaBound`](./extractionareabound/). Om satt till falskt kommer subpaths som inte är helt inkluderade i [`ExtractionAreaBound`](./extractionareabound/) att extraheras. Standardvärdet är `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom‑element kan hamna i olika SVG‑filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Inbäddade XForms packas inte upp. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Hämtar och anger alternativet för att packa upp endast den XForm som motsvarar det angivna predikatet. |

### Se även

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


