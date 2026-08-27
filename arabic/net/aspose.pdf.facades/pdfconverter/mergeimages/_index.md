---
title: "PdfConverter.MergeImages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfConverter. تقوم بدمج قائمة من تدفقات الصور كتيار صورة واحد. صيغ الإخراج Png/jpg/tiff مدعومة في حالة استخدام صيغة غير مدعومة يتم ترميز تدفق الإخراج كـ Jpeg افتراضيًا"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

يدمج قائمة تدفقات الصور في تدفق صورة واحد. صيغ الإخراج Png/jpg/tiff مدعومة، وفي حالة استخدام صيغة غير مدعومة يتم ترميز تدفق الإخراج كـ Jpeg افتراضيًا.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputImagesStreams | List`1 | قائمة تدفقات الصور للدمج. |
| outputImageFormat | ImageFormat | صيغة إخراج الصورة لتدفق الدمج. |
| mergeMode | ImageMergeMode | وضع الدمج. يُستخدم لتنسيقات Png/Jpg. |
| horizontal | Nullable`1 | النسبة الأفقية لتحديد عرض القماش لتدفق صورة الإخراج. يُستخدم لتنسيقات Png/Jpg مع ImageMergeMode.Center فقط. |
| vertical | Nullable`1 | النسبة العمودية لتحديد ارتفاع القماش لتدفق صورة الإخراج. يُستخدم لتنسيقات Png/Jpg مع ImageMergeMode.Center فقط. |

### قيمة الإرجاع

تيار الصورة مُرمّز بصيغة صورة الإخراج.

### انظر أيضًا

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


