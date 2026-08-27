---
title: "Klass OptimizationOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Optimization.OptimizationOptions class. Klass som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources."
type: docs
weight: 8120
url: /sv/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Klassen som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources().

```csharp
public class OptimizationOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Om true page contents kommer att återanvändas när document optimeras för lika pages. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Om denna flagga är satt till `true` kommer Pdf-objekt att packas in i Objest Streams och komprimeras för att minska pdf-filens storlek. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Uppsättning av alternativ som beskriver hur bilder i dokumentet ska komprimeras och parametrarna för komprimeringen. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Bildkodning som kommer att användas. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Om denna flagga är satt till true kommer Resource streams att analyseras. Om dubblettströmmar hittas (dvs. om strömmens innehåll är lika) kommer dessa strömmar att lagras som ett objekt. Detta möjliggör att minska dokumentets storlek i vissa fall (till exempel när samma dokument har concatenedted flera gånger). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Ta bort privat information (page piece info). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Om denna flagga är satt till true kommer alla document-objekt att kontrolleras och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Om denna flagga är satt till true kontrolleras varje resource för dess användning. Om en resource aldrig används tas resource bort. Detta kan minska dokumentets storlek, till exempel när sidor har extraherats från document. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Typsnitt kommer att konverteras till delmängder om de är satta till true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Gör så att typsnitt inte bäddas in om de är satta till true. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Skapar en optimeringsstrategi med alla alternativ aktiverade. Observera att endast de alternativ som inte förändrar någon funktionalitet i dokumentet aktiveras. Dvs. bildkomprimering och avbäddning av typsnitt kommer inte att aktiveras (och kan bäddas in manuellt). |

### Se även

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


