---
title: "Klassen RenderingOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.RenderingOptions-klass. Representerar renderingsalternativ"
type: docs
weight: 9910
url: /sv/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

Representerar renderingsalternativ.

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
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via !:FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Hämtar eller anger läge för streckkodoptimering. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indikerar att alla teckensnitt kommer att konverteras till TTF-unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt bara innehåller de symboler som används i texten, inte alla symboler från källteckensnittet. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Hämtar/anger standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Hämtar eller anger ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel på avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Hämtar eller anger högkvalitetsläge för interpolering. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Maximalt antal symboler i symbolcache. Standardvärdet är 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Hämtar eller anger läge för optimering av dimensioner. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Hämtar eller anger ett läge där systemteckensnitt renderas inbyggt. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Användning av denna flagga aktiverar teckensnittshintningsmekanismen. Teckensnittshintning är användningen av matematiska instruktioner för att justera visningen av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande kan användning av denna flagga endast ha effekt för TTF‑teckensnitt, om dessa teckensnitt används i källdokumentet. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Hämtar eller anger ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


