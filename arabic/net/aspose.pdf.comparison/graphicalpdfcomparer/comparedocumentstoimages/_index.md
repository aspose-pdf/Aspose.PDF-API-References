---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة GraphicalPdfComparer. تقارن المستندات رسوميًا. نتيجة المقارنة توضع في صور."
type: docs
weight: 50
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

يقارن المستندات رسوميًا. يتم وضع نتيجة المقارنة في صور.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document1 | Document | المستند الأول للمقارنة. |
| document2 | Document | المستند الثاني للمقارنة. |
| targetDirectory | String | الدليل لحفظ نتائج المقارنة. |
| fileNamePrefix | String | بادئة اسم الصور. |
| imageFormat | ImageFormat | تنسيق الصورة للحفظ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | إذا كانت الصفحات التي يتم مقارنتها بأحجام مختلفة. إذا كان targetDirectory فارغًا أو يساوي null. إذا كان fileNamePrefix فارغًا أو يساوي null. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


