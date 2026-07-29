---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة GraphicalPdfComparer. تقارن الصفحات رسوميًا. نتيجة المقارنة توضع في مستند PDF."
type: docs
weight: 80
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| page1 | صفحة | الصفحة الأولى. |
| page2 | صفحة | الصفحة الثانية. |
| resultPdfPath | String | المسار إلى ملف PDF الهدف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها ذات أحجام مختلفة. إذا كان resultPdfPath فارغًا أو سلسلة فارغة. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| page1 | صفحة | الصفحة الأولى. |
| page2 | صفحة | الصفحة الثانية. |
| pdfDocument | Document | مثيل مستند PDF. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها ذات أحجام مختلفة. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


