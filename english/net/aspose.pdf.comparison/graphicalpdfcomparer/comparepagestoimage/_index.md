---
title: "GraphicalPdfComparer.ComparePagesToImage"
linktitle: "ComparePagesToImage"
articleTitle: "ComparePagesToImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicalPdfComparer method. Compares pages graphically. The comparison result is placed in a image."
type: docs
weight: 60
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/"
product_version: "26.9.0"
---
## ComparePagesToImage([Page](../../../aspose.pdf/page/), [Page](../../../aspose.pdf/page/), string) {#comparepagestoimage}

Compares pages graphically. The comparison result is placed in a image.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The second page to compare. |
| resultImagePath | string | The path to target image file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes.
 If resultImagePath is null or empty string.
 There is unknown saving image format. |

### See Also

* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

