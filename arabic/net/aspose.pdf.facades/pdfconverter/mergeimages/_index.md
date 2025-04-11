---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfConverter. تدمج قائمة من تدفقات الصور كتيار صورة واحد. يتم دعم تنسيقات الإخراج Png/jpg/tiff في حالة استخدام تيار إخراج بتنسيق غير مدعوم مشفر كـ Jpeg بشكل افتراضي
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## طريقة PdfConverter.MergeImages

تدمج قائمة من تدفقات الصور كتيار صورة واحد. يتم دعم تنسيقات الإخراج Png/jpg/tiff، في حالة استخدام تيار إخراج بتنسيق غير مدعوم مشفر كـ Jpeg بشكل افتراضي.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputImagesStreams | List`1 | قائمة تدفقات الصور للتجميع. |
| outputImageFormat | ImageFormat | تنسيق الصورة الناتجة لتدفق الصورة المدمجة. |
| mergeMode | ImageMergeMode | وضع الدمج. يستخدم لتنسيقات Png/Jpg. |
| horizontal | Nullable`1 | النسبة الأفقية لتعيين عرض القماش لتدفق الصورة الناتجة. يستخدم لتنسيقات Png/Jpg مع ImageMergeMode.Center فقط. |
| vertical | Nullable`1 | النسبة الرأسية لتعيين ارتفاع القماش لتدفق الصورة الناتجة. يستخدم لتنسيقات Png/Jpg مع ImageMergeMode.Center فقط. |

### قيمة الإرجاع

تيار صورة مشفر كتنسيق الصورة الناتجة.

### انظر أيضًا

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)