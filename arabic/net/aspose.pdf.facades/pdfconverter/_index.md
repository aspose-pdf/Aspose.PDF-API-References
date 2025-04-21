---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfConverter. تمثل فئة لتحويل كل صفحة من ملفات PDF إلى صور تدعم BMP و JPEG و PNG و TIFF الآن. المحتوى المدعوم في ملفات PDF الصور، النماذج، التعليقات.
type: docs
weight: 4440
url: /ar/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

تمثل فئة لتحويل كل صفحة من ملف PDF إلى صور، تدعم BMP و JPEG و PNG و TIFF الآن. المحتوى المدعوم في ملفات PDF: الصور، النماذج، التعليقات.

```csharp
public sealed class PdfConverter : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | يقوم بتهيئة كائن `PdfConverter` جديد. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfConverter` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (Media/Crop boxes). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | يحصل أو يحدد موضع النهاية الذي ترغب في تحويله. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع عرض النموذج. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | يحصل على عدد الصفحات. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | يحصل أو يحدد OwnerPassword للمستند. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | يحصل أو يحدد الدقة أثناء التحويل. كلما زادت الدقة، كانت سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | يحصل أو يحدد موضع البداية الذي ترغب في تحويله. القيمة الدنيا هي 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | يحصل أو يحدد UserPassword للمستند. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | يربط تدفق PDF للتحويل. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | يربط ملف PDF للتحويل. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | يغلق مثيل PdfConverter ويحرر الموارد. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | يقوم ببعض الأعمال الأولية لتحويل مستند PDF إلى صور. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | يحفظ الصورة في التدفق مع تنسيق الصورة الافتراضي - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | يحفظ الصورة في ملف مع تنسيق الصورة الافتراضي - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | يحفظ الصورة في التدفق مع تنسيق الصورة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | يحفظ الصورة في التدفق مع حجم الصفحة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | يحفظ الصورة في ملف مع تنسيق الصورة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | يحفظ الصورة في ملف مع حجم الصفحة المحدد وتنسيق الصورة الافتراضي - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | يحفظ الصورة في التدفق مع تنسيق الصورة المحدد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | يحفظ الصورة في التدفق مع حجم الصفحة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | يحفظ الصورة في ملف مع تنسيق الصورة المحدد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | يحفظ الصورة في ملف مع حجم الصفحة المحدد وتنسيق الصورة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | يحفظ الصورة في التدفق مع تنسيق الصورة المحدد، الحجم والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | يحفظ الصورة في التدفق مع حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | يحفظ الصورة في ملف مع تنسيق الصورة المحدد والأبعاد. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | يحفظ الصورة في ملف مع حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | يحفظ الصورة في التدفق مع تنسيق الصورة المحدد، الحجم والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | يحفظ الصورة في التدفق مع تنسيق الصورة المحدد، الأبعاد والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | يحفظ الصورة في ملف مع تنسيق الصورة المحدد، حجم الصورة والجودة. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | يحفظ الصورة في ملف مع تنسيق الصورة المحدد، الأبعاد والجودة. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | يشير إلى ما إذا كان ملف PDF يحتوي على المزيد من الصور أم لا. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع حجم الصفحة ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع حجم الصفحة ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع حجم الصفحة ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع حجم الصفحة ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | يقوم بتحويل كل صفحات مستند PDF إلى صور مع الأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في تدفق TIFF ClassF واحد. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | يدمج قائمة من تدفقات الصور كتيار صورة واحد. تنسيقات المخرجات Png/jpg/tiff مدعومة، في حالة استخدام تنسيق غير مدعوم يتم ترميز تدفق الإخراج كـ JPEG بشكل افتراضي. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | يدمج قائمة من تدفقات TIFF كتيار TIFF متعدد الإطارات واحد. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)