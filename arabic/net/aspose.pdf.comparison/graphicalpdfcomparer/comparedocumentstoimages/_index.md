---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: طريقة GraphicalPdfComparer. تقارن الوثائق بشكل رسومي. يتم وضع نتيجة المقارنة في الصور
type: docs
weight: 50
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## طريقة GraphicalPdfComparer.CompareDocumentsToImages

تقارن الوثائق بشكل رسومي. يتم وضع نتيجة المقارنة في الصور.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| document1 | Document | الوثيقة الأولى للمقارنة. |
| document2 | Document | الوثيقة الثانية للمقارنة. |
| targetDirectory | String | الدليل لحفظ نتائج المقارنة. |
| fileNamePrefix | String | بادئة اسم الصور. |
| imageFormat | ImageFormat | تنسيق الصورة للحفظ. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها بأحجام مختلفة. إذا كان targetDirectory فارغًا أو سلسلة فارغة. إذا كان fileNamePrefix فارغًا أو سلسلة فارغة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)