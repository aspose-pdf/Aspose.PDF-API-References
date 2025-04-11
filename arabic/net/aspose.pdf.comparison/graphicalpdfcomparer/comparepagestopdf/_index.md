---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة GraphicalPdfComparer. تقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF
type: docs
weight: 80
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

تقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | الصفحة الأولى. |
| page2 | Page | الصفحة الثانية. |
| resultPdfPath | String | المسار إلى ملف PDF المستهدف. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها بأحجام مختلفة. إذا كان resultPdfPath فارغًا أو سلسلة فارغة. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

تقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | الصفحة الأولى. |
| page2 | Page | الصفحة الثانية. |
| pdfDocument | Document | مثيل مستند PDF. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها بأحجام مختلفة. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)