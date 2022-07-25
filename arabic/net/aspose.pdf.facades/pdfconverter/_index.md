---
title: PdfConverter
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لتحويل كل صفحة من ملف pdf إلى صور  ويدعم BMP و JPEG و PNG و TIFF الآن. المحتوى المدعوم في ملفات pdf الصور والنموذج والتعليق.
type: docs
weight: 2450
url: /ar/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

يمثل فئة لتحويل كل صفحة من ملف pdf إلى صور ، ويدعم BMP و JPEG و PNG و TIFF الآن. المحتوى المدعوم في ملفات pdf: الصور والنموذج والتعليق.

```csharp
public sealed class PdfConverter : Facade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | تهيئة جديد[`PdfConverter`](../pdfconverter) الكائن . |
| [PdfConverter](pdfconverter#constructor_1)(Document) | تهيئة جديد[`PdfConverter`](../pdfconverter) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | الحصول على نوع إحداثيات الصفحة أو تعيينه (مربعات الوسائط / الاقتصاص). يتم استخدام قيمة كروبوكس افتراضيًا. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | الحصول على أو تحديد الموضع النهائي الذي تريد تحويله. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | الحصول على أو تعيين وضع العرض التقديمي . |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | الحصول على عدد الصفحات . |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | الحصول على أو تعيين كلمة مرور مالك المستند. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | الحصول على خيارات التقديم أو تعيينها . |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | الحصول على الدقة أو تعيينها أثناء التحويل. كلما زادت الدقة ، كانت سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | الحصول على أو تحديد موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | الحصول على أو تعيين كلمة مرور مستخدم المستند. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | يربط دفق Pdf للتحويل. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | يربط ملف PDF للتحويل. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | أغلق مثيل PdfConverter وحرر الموارد. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | قم ببعض الأعمال الأولية لتحويل مستند pdf إلى صور. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | يحفظ الصورة للتدفق بتنسيق الصورة الافتراضي - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | يحفظ الصورة في ملف بتنسيق الصورة الافتراضي - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | يحفظ الصورة للتدفق باستخدام تنسيق الصورة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | يحفظ الصورة للتدفق بحجم الصفحة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | يحفظ الصورة في ملف بتنسيق صورة givin . |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | يحفظ الصورة في ملف بحجم الصفحة المحدد وتنسيق الصورة الافتراضي - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | يحفظ الصورة للتدفق باستخدام تنسيق وجودة صورة محددين. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | يحفظ الصورة للتدفق بحجم الصفحة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | يحفظ الصورة في ملف بتنسيق وجودة معينين للصورة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | يحفظ الصورة في ملف بحجم الصفحة وتنسيق الصورة المحددين. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | يحفظ الصورة للدفق بتنسيق صورة givin وحجمها وجودتها. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | يحفظ الصورة للتدفق مع تحديد حجم الصفحة وتنسيق الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | يحفظ الصورة في ملف بتنسيق وأبعاد الصورة المحددة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | يحفظ الصورة في ملف بحجم الصفحة وتنسيق الصورة وجودتها. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | يحفظ الصورة للدفق بتنسيق صورة givin وحجمها وجودتها. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | يحفظ الصورة للتدفق باستخدام تنسيق صورة givin والأبعاد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | يحفظ الصورة في ملف بتنسيق صورة givin وحجمها وجودتها. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | يحفظ الصورة في ملف بتنسيق وأبعاد وجودة الصورة المحددة. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | يشير إلى ما إذا كان ملف pdf يحتوي على صور أكثر أم لا. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | يحول كل صفحات مستند pdf إلى صور بها ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | يحول كل صفحات مستند pdf إلى صور بها ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | يدمج قائمة تدفقات الصور كتدفق صورة واحد. يتم دعم تنسيقات مخرجات Png / jpg / tiff ، في حالة استخدام دفق إخراج بتنسيق غير مدعوم مشفر بتنسيق Jpeg افتراضيًا. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | يدمج قائمة تدفقات tiff كتيار واحد متعدد الإطارات. |

### أنظر أيضا

* class [Facade](../facade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
