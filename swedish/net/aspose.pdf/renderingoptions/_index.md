---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions klass. Representerar renderingalternativ
type: docs
weight: 9760
url: /sv/net/aspose.pdf/renderingoptions/
---
## RenderingOptions klass

Representerar renderingalternativ.

```csharp
public sealed class RenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Ersätter typsnitt vid behov för att säkerställa att alla tecken i texten kan visas. Typsnittsersättningsalgoritmen följer dessa steg: 1. Om användaren uttryckligen ställer in egenskapen DefaultFontName, kontrollera om det angivna typsnittet kan visa de önskade tecknen. 2. Om inget användardefinierat typsnitt är inställt, sök igenom typsnitt som lagts till via !:FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå typsnittsnamn därefter. Försök att lokalisera och använda dessa typsnitt från systemet. 4. Som en fallback, sök i systemet efter något typsnitt som kan visa de nödvändiga tecknen. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Hämtar eller ställer in läget för streckkodoptimering. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indikerar att alla typsnitt kommer att konverteras till TTF unicode-versioner. Det är användbart av kompatibilitetsskäl och för att optimera typsnittsanvändning, eftersom varje nytt TTF-typsnitt inte kommer att ha alla symboler från källtypsnittet, utan endast symboler som används i texten. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Hämtar/ställer in det standardnamn på typsnitt som används för att ersätta saknade typsnitt. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller ställer in indikation på att fel relaterade till avsaknad av typsnitt kommer att ignoreras. true - betyder att fel avsaknad av typsnitt kommer att ignoreras. Textsegment som hänvisar till felaktiga resurser kommer att hoppas över under bearbetning. false som standard |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Hämtar eller ställer in högkvalitetsläge för interpolation. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Maximalt antal typsnitt i typsnitts-cache. Standardvärdet är 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Maximalt antal symboler i symbol-cache. Standardvärdet är 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Hämtar eller ställer in läget för att optimera dimensioner. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Hämtar eller ställer in ett läge där systemtypsnitt renderas nativt. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Användning av denna flagga aktiverar typsnitts-hintingmekanismen. Typsnitts-hinting är användningen av matematiska instruktioner för att justera visningen av ett konturtypsnitt. I vissa fall kan aktivering av denna flagga lösa problem med textens läsbarhet. För närvarande kan användningen av denna flagga ge effekt endast för TTF-typsnitt, om dessa typsnitt används i källdokumentet. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |

### Se Även

* namnrum [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)