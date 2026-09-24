---
title: "GraphicalPdfComparer Class"
linktitle: "GraphicalPdfComparer"
articleTitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer class. Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mai..."
type: docs
weight: 80
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/"
keywords: "GraphicalPdfComparer, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## GraphicalPdfComparer class

Represents a class for graphically comparing PDF documents.
 Should be used to search for small changes, mainly of a graphical nature.
 To compare text content changes, use other PDF comparison classes.

```csharp
public class GraphicalPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicalPdfComparer](./graphicalpdfcomparer/#constructor) | Initializes a new instance of the GraphicalPdfComparer class. |

## Properties

| Name | Description |
| --- | --- |
| [Color](./color/) { get; set; } | Gets and sets the change flag color. |
| [Resolution](./resolution/) { get; set; } | Gets and sets the resolution of the resulting images. |
| [Threshold](./threshold/) { get; set; } | Gets and sets the threshold value in percentage. |

## Methods

| Name | Description |
| --- | --- |
| [CompareDocumentsToImages](./comparedocumentstoimages/)(*Document, Document, string, string, ImageFormat*) | Compares documents graphically. The comparison result is placed in images. |
| [CompareDocumentsToPdf](./comparedocumentstopdf/)(*Document, Document, string*) | Compares documents graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToImage](./comparepagestoimage/)(*Page, Page, string*) | Compares pages graphically. The comparison result is placed in a image. |
| [ComparePagesToPdf](./comparepagestopdf/)(*Page, Page, string*) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToPdf](./comparepagestopdf/)(*Page, Page, Document*) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [GetDifference](./getdifference/)(*Page, Page*) | Gets differences between pages images. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

