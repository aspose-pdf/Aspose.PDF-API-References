---
title: "الفئة GraphicalPdfComparer"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer الفئة. تمثل فئة للمقارنة الرسومية لمستندات PDF. يجب استخدامها للبحث عن تغييرات صغيرة ذات طبيعة رسومية في المقام الأول. لمقارنة تغييرات محتوى النص استخدم فئات مقارنة PDF الأخرى"
type: docs
weight: 3300
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

يمثّل فئة للمقارنة الرسومية بين PDF documents. يجب استخدامها للبحث عن تغييرات صغيرة، خاصةً ذات طبيعة رسومية. لمقارنة تغييرات محتوى النص، استخدم فئات مقارنة PDF الأخرى.

```csharp
public class GraphicalPdfComparer
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | يحصل على ويضبط لون علم التغيير. اللون الافتراضي هو الأحمر. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | يحصل على ويضبط دقة الصور الناتجة. القيمة الافتراضية هي 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | يحصل على ويضبط قيمة العتبة بالنسبة المئوية. تسمح لك هذه القيمة بتجاهل التغييرات الصغيرة إذا لم تكن ذات أهمية بالنسبة لك. القيمة الافتراضية هي 0%. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | يقارن المستندات رسوميًا. يتم وضع نتيجة المقارنة في صور. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | يقارن المستندات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في صورة. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | يحصل على الفروقات بين صور الصفحات. النتيجة تحتوي على صورة للصفحة الأولى المقارنة ومصفوفة من الفروقات. |

### انظر أيضًا

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


