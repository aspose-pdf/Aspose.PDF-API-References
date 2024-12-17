---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer method. Compares documents graphically. The comparison result is placed in images
type: docs
weight: 50
url: /net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

Compares documents graphically. The comparison result is placed in images.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | The first document to compare. |
| document2 | Document | The second document to compare. |
| targetDirectory | String | The directory to save a comparison results. |
| fileNamePrefix | String | The images name prefix. |
| imageFormat | ImageFormat | The image format to save. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. If targetDirectory is null or empty string. If fileNamePrefix is null or empty string. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


