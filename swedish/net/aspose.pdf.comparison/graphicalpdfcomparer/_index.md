---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer klass. Representerar en klass för grafisk jämförelse av PDF-dokument. Ska användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra textinnehållsförändringar, använd andra PDF-jämförelseklasser.
type: docs
weight: 3190
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer klass

Representerar en klass för grafisk jämförelse av PDF-dokument. Ska användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra textinnehållsförändringar, använd andra PDF-jämförelseklasser.

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
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Hämtar och sätter färgen för förändringsflaggan. Standardfärgen är röd. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Hämtar och sätter upplösningen för de resulterande bilderna. Standardvärdet är 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Hämtar och sätter tröskelvärdet i procent. Detta värde gör att du kan ignorera små förändringar om de inte är betydelsefulla för dig. Standardvärdet är 0%. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Jämför dokument grafiskt. Jämförelseresultatet placeras i bilder. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Jämför dokument grafiskt. Jämförelseresultatet placeras i ett PDF-dokument. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Jämför sidor grafiskt. Jämförelseresultatet placeras i en bild. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Jämför sidor grafiskt. Jämförelseresultatet placeras i ett PDF-dokument. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Jämför sidor grafiskt. Jämförelseresultatet placeras i ett PDF-dokument. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Hämtar skillnader mellan sidbilder. Resultatet innehåller en bild av den första jämförda sidan och en array av skillnader. |

### Se Även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)