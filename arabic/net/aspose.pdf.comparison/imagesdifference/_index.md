---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ImagesDifference class. تمثل فئة النتيجة لمقارنة صفحتين PDF
type: docs
weight: 3230
url: /ar/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

تمثل فئة النتيجة لمقارنة صفحتين PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | يحصل على مصفوفة الفرق. هذه المصفوفة مشابهة لمصفوفة بيانات الصورة الأصلية التي تم الحصول عليها نتيجة لطريقة LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | ارتفاع الفرق. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | يحصل على صورة الصفحة الأولى المقارنة. الصورة لها تنسيق بكسل 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | خطوة بيانات صورة الفرق. |

## Methods

| Name | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | يحول مصفوفة الفرق إلى صورة بت ماب باستخدام الألوان المحددة. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | ينفذ أي عمليات تنظيف ضرورية قبل تدمير الكائن. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | يعيد بت ماب جديدة تمثل الصورة الوجهة من خلال تطبيق مصفوفة الفرق على الصورة المصدر. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)