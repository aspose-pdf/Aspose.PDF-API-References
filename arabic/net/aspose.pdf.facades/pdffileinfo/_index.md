---
title: PdfFileInfo
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF.
type: docs
weight: 2530
url: /ar/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

يمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | يقوم بتهيئة مثيل جديد لفئة Aspose.Pdf.Facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | تهيئة جديد[`PdfFileInfo`](../pdffileinfo) كائن على قاعدة*document* . |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | تهيئة نسخة جديدة من فئة Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | تهيئة نسخة جديدة من فئة Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | تهيئة نسخة جديدة من فئة Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | تهيئة نسخة جديدة من فئة Aspose.Pdf.Facades.PdfFileInfo. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | الحصول على أو تعيين معلومات المؤلف لمستند PDF . |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | الحصول على أو تعيين معلومات تاريخ الإنشاء لمستند PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | الحصول على أو تعيين معلومات المنشئ لمستند PDF . |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | يعود صحيحًا إذا كان ملف الإدخال الحالي عبارة عن ملف "Portfolio" يحتوي على مجموعة من ملفات PDF فيه. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | إرجاع صحيح إذا كانت هناك حاجة إلى كلمة مرور لتعديل الأذونات أو خاصية أمان المستند. انتبه إلى أنه لا يمكن قراءة هذه الخاصية إلا إذا تم توفير كلمة مرور صالحة في[`PdfFileInfo`](../pdffileinfo) منشئ . في حالة تعذر الوصول إلى PasswordType (يعني أنه تم توفير كلمة مرور غير صالحة) ستفشل قراءة هذه الخاصية مع[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception) . |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | يتم إرجاع صحيح إذا كانت كلمة المرور مطلوبة لفتح مستند pdf محمي بكلمة مرور. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | الحصول على المعلومات المخصصة لمستند PDF أو تعيينها. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | للتحقق مما إذا كان مستند PDF مشفرًا. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | للتحقق مما إذا كان إدخال المصدر هو ملف PDF صالح. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | الحصول على أو تعيين معلومات الكلمات الرئيسية لوثيقة PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | الحصول على أو تعيين معلومات تاريخ التعديل لمستند PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | الحصول على عدد صفحات المستند. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | إرجاع نوع كلمة المرور التي تم تمريرها لإنشاء مثيل PdfFileInfo. انظر القيم الممكنة في[`PasswordType`](./passwordtype) . انتبه إلى أنه يمكن فتح مستند pdf باستخدام كلمة مرور المستخدم (أو فتح) والمالك (أو أذونات التحرير). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | الحصول على معلومات المُنتِج لمستند PDF . |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | الحصول على أو تعيين معلومات الموضوع لمستند PDF . |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | الحصول على أو تعيين معلومات العنوان لمستند PDF . |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | تستخدم قواعد تحقق صارمة من خلال استخدام[`IsPdfFile`](./ispdffile) الملكية . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | مسح كافة المعلومات الوصفية لمستند PDF . |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | إلغاء تهيئة المثيل. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | الحصول على إعدادات امتياز مستند PDF . |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | الحصول على معلومات مخصصة لمستند PDF باسم الخاصية. إذا لم تكن هناك خاصية تطابق الاسم ، فستُرجع سلسلة فارغة. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | الحصول على ارتفاع الصفحة المحددة. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | الحصول على تدوير للصفحة المحددة. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | الحصول على عرض الصفحة المحددة. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | الحصول على الإزاحة الأفقية لمنطقة عرض الصفحة المحددة. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | الحصول على الإزاحة الرأسية لمنطقة عرض الصفحة المحددة. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | الحصول على معلومات إصدار مستند PDF . |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | يحفظ مستند PDF في الملف المحدد. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | يحفظ مستند PDF في الملف المحدد. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | احفظ مستند PDF المحدث في الملف المحدد. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | يغير الخصائص المحددة صراحة عن طريق تعيين معلومات الملف ، وتبقى الخصائص الأخرى. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | لتعيين المعلومات المخصصة لمستند PDF . |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
