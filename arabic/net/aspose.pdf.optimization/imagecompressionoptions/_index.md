---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Optimization.ImageCompressionOptions. تحتوي الفئة على مجموعة من الخيارات لضغط الصور
type: docs
weight: 7950
url: /ar/net/aspose.pdf.optimization/imagecompressionoptions/
---
## فئة خيارات ضغط الصور

تحتوي الفئة على مجموعة من الخيارات لضغط الصور.

```csharp
public class ImageCompressionOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | إذا تم تعيين هذه العلامة على true، سيتم ضغط الصور في المستند. يتم تحديد مستوى الضغط باستخدام خاصية ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | يحصل أو يحدد الترميز المستخدم لتخزين الصور. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | يحدد مستوى ضغط الصورة عند استخدام علامة CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | يحدد الحد الأقصى لدقة الصور. إذا كانت الصورة ذات دقة أعلى، فسيتم تغيير حجمها. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | إذا تم تعيين هذه العلامة على true و CompressImages هو true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من معلمة MaxResolution المحددة. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن أسرع من القياسي ولكن قد لا يكون قابلاً للتطبيق على جميع الصور)، 3. مختلط (يتم تطبيق الضغط القياسي على الصور التي لا يمكن ضغطها بواسطة الخوارزمية الأسرع، قد يعطي هذا أفضل ضغط ولكنه أبطأ من خوارزمية "سريع". الإصدار "سريع" غير قابل للتطبيق لتغيير حجم الصور (سيتم استخدام الطريقة القياسية). الافتراضي هو "قياسي". |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* التجميع [Aspose.PDF](../../)