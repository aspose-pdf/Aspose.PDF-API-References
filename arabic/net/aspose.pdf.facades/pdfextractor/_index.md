---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfExtractor. فئة لاستخراج الصور والنصوص من مستند PDF
type: docs
weight: 4450
url: /ar/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

فئة لاستخراج الصور والنصوص من مستند PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initializes new `PdfExtractor` object. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initializes new `PdfExtractor` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | يحصل أو يحدد الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | يحدد الوضع لعملية استخراج الصور. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | يحدد الوضع لنتيجة استخراج النص. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | يكون صحيحًا عندما يحتوي النص على رموز عبرية أو عربية. يجب أن تؤخذ هذه الحالة بعين الاعتبار بشكل خاص لأن دوال السلسلة تغير سلوكها وتبدأ في معالجة النص من اليمين إلى اليسار (باستثناء الأرقام وغيرها من الأحرف غير النصية). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | يحصل أو يحدد كلمة مرور الملف المدخل. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | يحدد أو يحصل على الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي تحتوي على قيمة دقة أكبر تكون أكثر وضوحًا. ومع ذلك، فإن زيادة قيمة الدقة تؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة، يكفي ضبط الدقة على 150 أو 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | يحصل أو يحدد الصفحة الأولى في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | يحصل أو يحدد خيارات بحث النص. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | يربط مستند PDF من الدفق. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | يربط ملف PDF المدخل. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يتخلص من Aspose.Pdf.Document المرتبط بواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | يستخرج المرفقات من مستند PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | يستخرج المرفق إلى ملف PDF حسب اسم المرفق. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | يستخرج الصور من ملف PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | يستخرج النص من مستند PDF باستخدام ترميز Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | يستخرج النص من مستند PDF باستخدام الترميز المحدد. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | يحفظ جميع ملفات المرفقات إلى الدفقات. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | يخزن المرفق في ملف. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | يحصل على قائمة المرفقات. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | يعيد قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق بالتنسيق المحدد للصورة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | يحفظ نص صفحة واحدة في الدفق. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | يحفظ نص صفحة واحدة في ملف. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | يحفظ النص في الدفق. انظر أيضًا: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | يحفظ النص في ملف. انظر أيضًا: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | يحفظ النص في الدفق. انظر أيضًا: [`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | يتحقق مما إذا كانت هناك المزيد من الصور المتاحة في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | يشير إلى ما إذا كان يمكن الحصول على المزيد من النصوص أم لا. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)