---
title: PdfExtractor
second_title: Aspose.PDF لمرجع .NET API
description: فئة لاستخراج الصور والنصوص من مستند PDF.
type: docs
weight: 2460
url: /ar/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

فئة لاستخراج الصور والنصوص من مستند PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | تهيئة جديد[`PdfExtractor`](../pdfextractor) الكائن . |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | تهيئة جديد[`PdfExtractor`](../pdfextractor) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | الحصول على أو تعيين صفحة النهاية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | يحدد وضع عملية استخراج الصور. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | يضبط الوضع الخاص بنتيجة استخراج النص. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | يكون هذا صحيحًا عندما يكون للنص رموز عبري أو عربي. يجب مراعاة هذه الحالة بشكل خاص لأن دالات السلسلة تغير سلوكها وتبدأ معالجة النص من اليمين إلى اليسار (باستثناء الأرقام والأحرف غير النصية الأخرى) . |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | الحصول على أو تعيين كلمة مرور ملف الإدخال. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | قم بتعيين أو الحصول على دقة للصور المستخرجة . القيمة الافتراضية هي 150. الصور التي لها قيمة دقة أكبر تكون أكثر وضوحًا . ومع ذلك ، تؤدي قيمة الدقة المتزايدة إلى زيادة الوقت والذاكرة اللازمتين لاستخراج الصور . عادةً ما يكفي الحصول على صورة واضحة. لضبط الدقة على 150 أو 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | الحصول على أو تعيين صفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | الحصول على أو تعيين خيارات البحث عن النص. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | ربط مستند PDF من الدفق . |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | ربط ملف إدخال PDF . |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf. وثيقة مرتبطة بواجهة . |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | لاستخراج المرفقات من مستند PDF . |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | لاستخراج المرفقات إلى ملف PDF حسب اسم المرفق. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | استخراج الصور من ملف PDF . |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | استخراج نص من مستند Pdf باستخدام ترميز Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | استخراج نص من مستند Pdf باستخدام ترميز محدد. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | يحفظ كل ملفات المرفقات في streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | تخزين المرفقات في ملف . |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | يحصل على قائمة المرفقات . |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | يقوم بإرجاع قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | استرجع الصورة التالية من ملف PDF وتخزينها في البث المباشر. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | استرجع الصورة التالية من ملف PDF وقم بتخزينها في البث باستخدام تنسيق الصورة المحدد. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | يسترجع الصورة التالية من مستند PDF بتنسيق معين للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | يحفظ نص صفحة واحدة للدفق. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | يحفظ نص صفحة واحدة في ملف. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | يحفظ النص للدفق. أنظر أيضا:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | يحفظ النص في ملف. أنظر أيضا:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | يحفظ النص للدفق. أنظر أيضا:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | للتحقق مما إذا كان يمكن الوصول إلى المزيد من الصور في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | يشير إلى إمكانية الحصول على المزيد من النصوص أم لا. |

### أنظر أيضا

* class [Facade](../facade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
