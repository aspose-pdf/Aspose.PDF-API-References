---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة GraphicalPdfComparer. تقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في صورة
type: docs
weight: 70
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## طريقة GraphicalPdfComparer.ComparePagesToImage

تقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في صورة.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| page1 | Page | الصفحة الأولى للمقارنة. |
| page2 | Page | الصفحة الثانية للمقارنة. |
| resultImagePath | String | المسار إلى ملف الصورة المستهدفة. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي تتم مقارنتها بأحجام مختلفة. إذا كان resultImagePath فارغًا أو سلسلة فارغة. هناك تنسيق صورة غير معروف للحفظ. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)