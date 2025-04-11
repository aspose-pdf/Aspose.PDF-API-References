---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer-Klasse. Stellt eine Klasse zum grafischen Vergleichen von PDF-Dokumenten dar. Sollte verwendet werden, um kleine Änderungen, hauptsächlich grafischer Natur, zu suchen. Um Änderungen im Textinhalt zu vergleichen, verwenden Sie andere PDF-Vergleichsklassen.
type: docs
weight: 3190
url: /de/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Klasse GraphicalPdfComparer

Stellt eine Klasse zum grafischen Vergleichen von PDF-Dokumenten dar. Sollte verwendet werden, um kleine Änderungen, hauptsächlich grafischer Natur, zu suchen. Um Änderungen im Textinhalt zu vergleichen, verwenden Sie andere PDF-Vergleichsklassen.

```csharp
public class GraphicalPdfComparer
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Ruft die Änderungsflagfarbe ab und legt sie fest. Die Standardfarbe ist rot. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Ruft die Auflösung der resultierenden Bilder ab und legt sie fest. Der Standardwert beträgt 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Ruft den Schwellenwert in Prozent ab und legt ihn fest. Dieser Wert ermöglicht es Ihnen, kleine Änderungen zu ignorieren, wenn sie für Sie nicht signifikant sind. Der Standardwert beträgt 0%. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in Bildern abgelegt. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem Bild abgelegt. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Ruft die Unterschiede zwischen Seitenbildern ab. Das Ergebnis enthält ein Bild der ersten verglichenen Seite und ein Array von Unterschieden. |

### Siehe auch

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)