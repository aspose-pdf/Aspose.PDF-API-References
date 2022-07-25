---
title: PdfFileStamp
second_title: Aspose.PDF لمرجع .NET API
description: فئة لإضافة الطوابع العلامة المائية أو الخلفية إلى ملفات PDF .
type: docs
weight: 2580
url: /ar/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

فئة لإضافة الطوابع (العلامة المائية أو الخلفية) إلى ملفات PDF .

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | مُنشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج من خلال الخصائص المقابلة. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | تهيئة جديد[`PdfFileStamp`](../pdffilestamp) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | الحصول على اسم المرفق أو تعيينه عند تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | الحصول على أو تعيين كيفية تخزين المحتوى عند تخزين نتيجة العملية في كائن HttpResponse. القيمة المحتملة: مضمنة / مرفق . الافتراضي: مضمنة . |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج في تنسيق الملف المحدد. إذا لم يتم تحديد هذه الخاصية ، فسيتم حفظ الملف بتنسيق PDF الافتراضي بدون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | يحافظ على الأمان إذا كان صحيحًا. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة) . |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | الحصول على نمط ترقيم الصفحات أو تعيينه. القيم الممكنة: NumeralsArabic، NumeralsRomanUppercase، NumeralsRomanLowercase، LettersAppercase، LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | الحصول على علامة التحسين أو تعيينها. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا كانت مجموعة العلامات هذه. هذا يسمح بتقليل حجم الملف الناتج ولكن قد يتسبب في إبطاء التنفيذ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false . |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | الحصول على ارتفاع الصفحة الأولى في ملف souorce . |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | الحصول على أو تعيين تدوير رقم الصفحة. الدوران بالدرجات. الافتراضي هو 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | الحصول على عرض الصفحة الأولى في ملف الإدخال. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | الحصول على كائن الاستجابة أو تعيينه حيث يتم تخزين نتيجة العملية. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | الحصول على أو تعيين خيارات الحفظ عند تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | معرف الطابع للطابع المضاف التالي (بما في ذلك رؤوس الصفحات / الأبواق / أرقام الصفحات) . |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | الحصول على أو تحديد رقم البداية للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. على سبيل المثال ، إذا تم تعيين رقم البداية على 100 ، فستحتوي صفحات المستند على أرقام 100 ، 101 ، 102 ... |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | إضافة تذييل إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | إضافة صورة كتذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | إضافة صورة كتذييل إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | إضافة تذييل إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | إضافة صورة كتذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | إضافة صورة كتذييل للصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | إضافة رأس الصفحة . |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | يضيف الصورة كرأس على الصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | إضافة صورة كرأس لصفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | إضافة رأس إلى صفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | إضافة صورة أعلى الصفحة. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | يضيف الصورة كرأس على الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة . يتم وضع رقم الصفحة في أسفل الصفحة في المنتصف أفقيًا . |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | أضف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة يتم توسيطه أفقيًا. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | يضيف رقم الصفحة في الموضع المحدد بالصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | يضيف رقم الصفحة في الموضع المحدد بالصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | يضيف طابعًا إلى الملف. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | لإغلاق الملفات المفتوحة وحفظ التغييرات. تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج ، فلن يتم إغلاقها بواسطة طريقة Close (). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | يحفظ المستند في تيار محدد. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | يحفظ النتيجة في الملف المحدد. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | الموضع الأيسر السفلي . |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | الموضع الأوسط السفلي . |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | الموضع الأيمن السفلي . |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | الموضع الأيسر . |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | الوضع الصحيح . |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | دع الموضع العلوي . |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | الموضع الأوسط العلوي . |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | الموضع العلوي الأيمن. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
