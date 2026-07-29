---
title: "الفئة ImagesDifference"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Comparison.ImagesDifference. تمثل فئة النتيجة لمقارنة صفحتي PDF."
type: docs
weight: 3340
url: /ar/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

يمثّل فئة نتيجة مقارنة PDF pages.

```csharp
public sealed class ImagesDifference : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | يحصل على مصفوفة الفروق. هذه المصفوفة مشابهة لمصفوفة بيانات الصورة الأصلية التي تم الحصول عليها نتيجةً لطريقة LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | ارتفاع الفارق. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | يحصل على صورة الصفحة الأولى التي تم مقارنتها. تنسيق البكسل للصورة هو 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | خطوة (stride) بيانات صورة الفارق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | يحوّل مصفوفة الفروق إلى صورة bitmap باستخدام الألوان المحددة. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | ينفّذ أي عمليات تنظيف ضرورية قبل تدمير الكائن. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | يعيد صورة bitmap جديدة تمثل الصورة الهدف عبر تطبيق مصفوفة الفروق على صورة المصدر. |

### انظر أيضًا

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


