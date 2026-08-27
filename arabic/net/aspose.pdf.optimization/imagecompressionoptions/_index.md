---
title: "الفئة ImageCompressionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions الفئة. الفئة تحتوي على مجموعة من الخيارات لضغط image."
type: docs
weight: 8090
url: /ar/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

الفئة تحتوي على مجموعة خيارات لضغط الصورة.

```csharp
public class ImageCompressionOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | إذا تم تعيين هذه العلامة إلى true، سيتم ضغط images في المستند. يتم تحديد مستوى الضغط باستخدام خاصية ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Gets أو sets encoding المستخدم لتخزين images. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | يحدد مستوى ضغط image عندما يتم استخدام علامة CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | يحدد الحد الأقصى لدقة الصور. إذا كانت الصورة ذات دقة أعلى سيتم تصغيرها |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | إذا تم تعيين هذه العلامة إلى true وكان CompressImages يساوي true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يوفر هذا أفضل ضغط لكنه أبطأ من الخوارزمية \"fast\". الإصدار \"Fast\" غير قابل لتغيير حجم الصور (سيُستخدم الطريقة القياسية). القيمة الافتراضية هي \"Standard\".) |

### انظر أيضًا

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


