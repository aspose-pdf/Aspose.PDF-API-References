---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions klass. Klass som beskriver dokumentoptimeringsalgoritm. Instans av denna klass kan användas som parameter för metoden OptimizeResources
type: docs
weight: 7980
url: /sv/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions klass

Klass som beskriver dokumentoptimeringsalgoritm. Instans av denna klass kan användas som parameter för metoden OptimizeResources().

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
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Om sant kommer sidinnehåll att återanvändas när dokumentet optimeras för lika sidor. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Om denna flagga är inställd på `true`, kommer Pdf-objekt att packas i Objest Streams och komprimeras för att minska pdf-filens storlek. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Uppsättning av alternativ som beskriver om bilder i dokumentet ska komprimeras och parametrar för komprimeringen. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Bildkodare som kommer att användas. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Om denna flagga är inställd på sant, kommer resursströmmar att analyseras. Om dubblettströmmar hittas (dvs. om ströminnehållet är lika), kommer dessa strömmar att lagras som ett objekt. Detta gör att dokumentstorleken kan minskas i vissa fall (till exempel när samma dokument har sammanfogats flera gånger). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Skanningsnivå. Djupare skanningar (högre värde) tar längre tid men kan ge mindre resultatfiler. Standardvärde: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Anger maximal upplösning för bilder. Om bilden har högre upplösning kommer den att skalas. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Ta bort privat information (sidstyckeinfo). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Om denna flagga är inställd på sant, kommer alla dokumentobjekt att kontrolleras och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Om denna flagga är inställd på sant, kontrolleras varje resurs för dess användning. Om resursen aldrig används, tas den bort. Detta kan minska dokumentstorleken, till exempel när sidor har extraherats från dokumentet. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Typsnitt kommer att konverteras till delmängder om inställt på sant. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Gör typsnitt icke-inbäddade om inställt på sant. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Skapar en optimeringsstrategi med alla alternativ aktiverade. Observera att endast alternativ som inte ändrar någon funktionalitet i dokumentet aktiveras. Dvs. bildkomprimering och typsnitt avinbäddning kommer inte att aktiveras (och kan inbäddas manuellt). |

### Se Även

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)