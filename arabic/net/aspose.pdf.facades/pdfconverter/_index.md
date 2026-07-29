---
title: "الفئة PdfConverter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfConverter. تمثل فئة لتحويل كل صفحة من ملفات pdf إلى صور تدعم BMP و JPEG و PNG و TIFF الآن. المحتوى المدعوم في pdfs صور من التعليقات"
type: docs
weight: 4560
url: /ar/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

يمثل فئة لتحويل كل صفحة من ملف pdf إلى صور، يدعم الآن BMP و JPEG و PNG و TIFF. المحتوى المدعوم في ملفات pdf: صور، نماذج، تعليقات.

```csharp
public sealed class PdfConverter : Facade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | يُنشئ كائن `PdfConverter` جديد. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | يُنشئ كائن `PdfConverter` جديد استنادًا إلى *document*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | يحصل أو يعيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox كإعداد افتراضي. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | يحصل أو يضبط موضع النهاية الذي تريد تحويله. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | يحصل على عدد الصفحات. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | يحصل أو يضبط OwnerPassword الخاص بالمستند. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | يحصل أو يضبط الدقة أثناء التحويل. كلما ارتفعت الدقة، كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | يحصل أو يضبط موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | يحصل أو يضبط UserPassword الخاص بالمستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf)(Document) | يربط مستند PDF بـ `PdfConverter` للمعالجة اللاحقة. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | يربط تدفق Pdf للتحويل. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | يربط ملف Pdf للتحويل. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | أغلق نسخة PdfConverter وأفرغ الموارد. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | قم ببعض الأعمال الأولية لتحويل مستند pdf إلى صور. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | يحفظ الصورة إلى تدفق بصيغة الصورة الافتراضية - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | يحفظ الصورة إلى ملف بصيغة الصورة الافتراضية - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | يحفظ الصورة إلى تدفق بصيغة صورة محددة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | يحفظ الصورة إلى تدفق بحجم صفحة محدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | يحفظ الصورة إلى ملف بصيغة صورة محددة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | يحفظ الصورة إلى ملف بحجم صفحة محدد وصيغة الصورة الافتراضية - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | يحفظ الصورة إلى تدفق بحجم صفحة محدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | يحفظ الصورة إلى ملف باستخدام حجم الصفحة المحدد وتنسيق الصورة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الحجم والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد والأبعاد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | يحفظ الصورة إلى ملف باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الحجم والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المعطى، الأبعاد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المعطى، حجم الصورة، والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد، الأبعاد والجودة. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | يشير إلى ما إذا كان ملف pdf يحتوي على صور إضافية أم لا. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | يدمج قائمة تدفقات الصور في تدفق صورة واحد. صيغ الإخراج Png/jpg/tiff مدعومة، وفي حالة استخدام صيغة غير مدعومة يتم ترميز تدفق الإخراج كـ Jpeg افتراضيًا. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | يدمج قائمة تدفقات tiff في تدفق tiff متعدد الإطارات واحد. |

### انظر أيضًا

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


