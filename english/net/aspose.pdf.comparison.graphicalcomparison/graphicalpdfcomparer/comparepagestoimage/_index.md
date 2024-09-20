---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer method. Compares pages graphically. The comparison result is placed in a image
type: docs
weight: 70
url: /net/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage method

Compares pages graphically. The comparison result is placed in a image.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The second page to compare. |
| resultImagePath | String | The path to target image file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. If resultImagePath is null or empty string. There is unknown saving image format. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison.GraphicalComparison](../../../aspose.pdf.comparison.graphicalcomparison/)
* assembly [Aspose.PDF](../../../)


