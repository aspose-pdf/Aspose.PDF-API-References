---
title: "فئة PdfExtractor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Facades.PdfExtractor class. فئة لاستخراج الصور والنص من مستند PDF"
type: docs
weight: 4570
url: /ar/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

فئة لاستخراج الصور والنص من مستند PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | يُنشئ كائن `PdfExtractor` جديد. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | يُنشئ كائن `PdfExtractor` جديد على أساس *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | يحصل أو يضبط صفحة النهاية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | يضبط الوضع لعملية استخراج الصور. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | يضبط الوضع لنتيجة استخراج النص. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | يكون صحيحًا عندما يحتوي النص على رموز عبرية أو عربية. يجب أخذ هذه الحالة في الاعتبار بشكل خاص لأن وظائف السلاسل تغير سلوكها وتبدأ معالجة النص من اليمين إلى اليسار (باستثناء الأرقام وغيرها من الأحرف غير النصية). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | يحصل أو يضبط كلمة مرور ملف الإدخال. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | يضبط أو يحصل على الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي لها قيمة دقة أعلى تكون أكثر وضوحًا. ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة يكفي ضبط الدقة على 150 أو 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | يحصل أو يضبط صفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | يحصل أو يعيّن خيارات بحث النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | يربط مستند PDF من الدفق. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | ربط ملف PDF الإدخال. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يفرغ Aspose.Pdf.Document المرتبط بواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | يستخرج المرفقات من مستند PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | يستخرج المرفق إلى ملف PDF حسب اسم المرفق. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | يستخرج الصور من ملف PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | يستخرج النص من مستند PDF باستخدام ترميز Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | يستخرج النص من مستند PDF باستخدام الترميز المحدد. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | يحفظ جميع ملفات المرفقات إلى تدفقات. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | يخزن المرفق في ملف. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | يحصل على قائمة المرفقات. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | يرجع قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | يسترجع الصورة التالية من ملف PDF ويخزنها في تدفق. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | يسترجع الصورة التالية من ملف PDF ويخزنها في تدفق بالتنسيق المحدد للصورة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | يحفظ نص صفحة واحدة إلى تدفق. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | يحفظ نص صفحة واحدة إلى ملف. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | يحفظ النص إلى تدفق. راجع أيضًا:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | يحفظ النص إلى ملف. راجع أيضًا:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | يحفظ النص إلى تدفق. راجع أيضًا:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | يتحقق مما إذا كانت هناك صور إضافية يمكن الوصول إليها في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | يشير إلى ما إذا كان يمكن الحصول على نصوص إضافية أم لا. |

### انظر أيضًا

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


