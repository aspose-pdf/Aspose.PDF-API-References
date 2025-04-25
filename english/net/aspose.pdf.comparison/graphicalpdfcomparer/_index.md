---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer class. Represents a class for graphically comparing PDF documents. Should be used to search for small changes mainly of a graphical nature. To compare text content changes use other PDF comparison classes
type: docs
weight: 3290
url: /net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mainly of a graphical nature. To compare text content changes, use other PDF comparison classes.

```csharp
public class GraphicalPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Gets and sets the change flag color. The default color is red. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Gets and sets the resolution of the resulting images. The default value is 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%. |

## Methods

| Name | Description |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Compares documents graphically. The comparison result is placed in images. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Compares documents graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Compares pages graphically. The comparison result is placed in a image. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Gets differences between pages images. The result contains an image of the first page compared and an array of differences. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


