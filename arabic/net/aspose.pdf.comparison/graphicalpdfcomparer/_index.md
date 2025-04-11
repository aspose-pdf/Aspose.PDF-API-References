---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer class. تمثل فئة لمقارنة مستندات PDF بشكل رسومي. يجب استخدامها للبحث عن التغييرات الصغيرة، بشكل رئيسي من الطبيعة الرسومية. لمقارنة تغييرات محتوى النص، استخدم فئات مقارنة PDF الأخرى.
type: docs
weight: 3190
url: /ar/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

تمثل فئة لمقارنة مستندات PDF بشكل رسومي. يجب استخدامها للبحث عن التغييرات الصغيرة، بشكل رئيسي من الطبيعة الرسومية. لمقارنة تغييرات محتوى النص، استخدم فئات مقارنة PDF الأخرى.

```csharp
public class GraphicalPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | يحصل على لون علامة التغيير ويضبطه. اللون الافتراضي هو الأحمر. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | يحصل على دقة الصور الناتجة ويضبطها. القيمة الافتراضية هي 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | يحصل على قيمة العتبة ويضبطها كنسبة مئوية. هذه القيمة تسمح لك بتجاهل التغييرات الصغيرة إذا لم تكن مهمة بالنسبة لك. القيمة الافتراضية هي 0%. |

## Methods

| Name | Description |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | يقارن المستندات بشكل رسومي. يتم وضع نتيجة المقارنة في الصور. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | يقارن المستندات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | يقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في صورة. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | يقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | يقارن الصفحات بشكل رسومي. يتم وضع نتيجة المقارنة في مستند PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | يحصل على الفروقات بين صور الصفحات. تحتوي النتيجة على صورة للصفحة الأولى المقارنة ومصفوفة من الفروقات. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)