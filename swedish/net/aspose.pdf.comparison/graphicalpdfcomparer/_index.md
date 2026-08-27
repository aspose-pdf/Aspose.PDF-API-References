---
title: "Klass GraphicalPdfComparer"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer klass. Representerar en klass för grafisk jämförelse av PDF-dokument. Bör användas för att söka efter små förändringar som huvudsakligen är av grafisk natur. För att jämföra förändringar i textinnehåll, använd andra PDF-jämförelsklasser."
type: docs
weight: 3300
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

Representerar en klass för grafisk jämförelse av PDF-dokument. Bör användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra ändringar i textinnehåll, använd andra PDF-jämförelsklasser.

```csharp
public class GraphicalPdfComparer
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Hämtar och anger färgen på förändringsflaggan. Standardfärgen är röd. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Jämför dokument grafiskt. Jämförelsresultatet placeras i bilder. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Jämför dokument grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Jämför sidor grafiskt. Jämförelsresultatet placeras i en bild. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Hämtar skillnader mellan sidbilder. Resultatet innehåller en bild av den första jämförda sidan och en matris av skillnader. |

### Se även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


