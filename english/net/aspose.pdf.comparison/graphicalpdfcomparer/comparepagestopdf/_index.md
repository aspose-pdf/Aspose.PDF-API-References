---
title: "GraphicalPdfComparer.ComparePagesToPdf"
linktitle: "ComparePagesToPdf"
articleTitle: "ComparePagesToPdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicalPdfComparer method. Compares pages graphically. The comparison result is placed in a PDF document."
type: docs
weight: 30
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/"
product_version: "26.9.0"
---
## ComparePagesToPdf([Page](../../../aspose.pdf/page/), [Page](../../../aspose.pdf/page/), string) {#comparepagestopdf}

Compares pages graphically. The comparison result is placed in a PDF document.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page. |
| page2 | Page | The second page. |
| resultPdfPath | String | The path to target pdf file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes.
 If resultPdfPath is null or empty string. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf([Page](../../../aspose.pdf/page/), [Page](../../../aspose.pdf/page/), [Document](../../../aspose.pdf/document/)) {#comparepagestopdf_1}

Compares pages graphically. The comparison result is placed in a PDF document.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page. |
| page2 | Page | The second page. |
| pdfDocument | Document | The pdf document instance. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

