---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
linktitle: "CompareDocumentsToImages"
articleTitle: "CompareDocumentsToImages"
second_title: "Aspose.PDF for .NET"
description: "Compares documents graphically. The comparison result is placed in images."
type: docs
weight: 70
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/"
product_version: "26.9.0"
---
## CompareDocumentsToImages([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), string, string, [ImageFormat](../../../aspose.pdf.drawing/imageformat/)) {#comparedocumentstoimages}

Compares documents graphically. The comparison result is placed in images.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | The first document to compare. |
| document2 | Document | The second document to compare. |
| targetDirectory | string | The directory to save a comparison results. |
| fileNamePrefix | string | The images name prefix. |
| imageFormat | ImageFormat | The image format to save. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes.
 If targetDirectory is null or empty string.
 If fileNamePrefix is null or empty string. |

### See Also

* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

