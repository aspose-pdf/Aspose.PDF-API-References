---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo class. يمثل فئة للوصول إلى المعلومات الوصفية لوثيقة PDF
type: docs
weight: 4520
url: /ar/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

يمثل فئة للوصول إلى المعلومات الوصفية لوثيقة PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class with default values. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initializes new `PdfFileInfo` object on base of the *document*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |

## Properties

| Name | Description |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | يحصل على أو يحدد معلومات المؤلف لوثيقة PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | يحصل على أو يحدد معلومات تاريخ الإنشاء لوثيقة PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | يحصل على أو يحدد معلومات المنشئ لوثيقة PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة الوثيقة التي يعمل عليها. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | يرجع true إذا كانت ملف الإدخال الحالي هو ملف 'محفظة' يحتوي على مجموعة من ملفات PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | يرجع true إذا كانت كلمة المرور مطلوبة لتعديل الأذونات أو خاصية أمان الوثيقة. انتبه إلى أن هذه الخاصية يمكن قراءتها فقط إذا تم توفير كلمة مرور صالحة في مُنشئ `PdfFileInfo`. في حالة أن نوع كلمة المرور هو غير قابل للوصول (يعني أنه تم توفير كلمة مرور غير صالحة) ستفشل قراءة هذه الخاصية مع [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | يرجع true إذا كانت كلمة المرور مطلوبة لفتح وثيقة PDF محمية بكلمة مرور. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | يحصل على أو يحدد المعلومات المخصصة لوثيقة PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | يتحقق مما إذا كانت وثيقة PDF مشفرة. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | يتحقق مما إذا كانت المدخلات المصدر هي ملف PDF صالح. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | يحصل على أو يحدد معلومات الكلمات الرئيسية لوثيقة PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | يحصل على أو يحدد معلومات تاريخ التعديل لوثيقة PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | يحصل على عدد صفحات الوثيقة. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | يرجع نوع كلمة المرور التي تم تمريرها لإنشاء مثيل PdfFileInfo. انظر القيم الممكنة في [`PasswordType`](./passwordtype/). انتبه إلى أن وثيقة PDF يمكن فتحها باستخدام كل من كلمة مرور المستخدم (أو كلمة المرور المفتوحة) وكلمة مرور المالك (أو الأذونات، التعديل). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | يحصل على معلومات المنتج لوثيقة PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | يحصل على أو يحدد معلومات الموضوع لوثيقة PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | يحصل على أو يحدد معلومات العنوان لوثيقة PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | يستخدم قواعد التحقق الصارمة عبر استخدام خاصية [`IsPdfFile`](./ispdffile/). |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Clears all meta information of PDF document. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Deinitializes the instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | يحصل على إعدادات أذونات وثيقة PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | يحصل على المعلومات المخصصة لوثيقة PDF مع اسم الخاصية. إذا لم يكن هناك تطابق مع الاسم، فسيتم إرجاع سلسلة فارغة. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | يحصل على ارتفاع الصفحة المحددة. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | يحصل على دوران الصفحة المحددة. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | يحصل على عرض الصفحة المحددة. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | يحصل على الإزاحة الأفقية لمنطقة عرض الصفحة المحددة. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | يحصل على الإزاحة الرأسية لمنطقة عرض الصفحة المحددة. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | يحصل على معلومات إصدار وثيقة PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Saves the PDF document to the specified file. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Saves the PDF document to the specified file. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Save updated PDF document into specified file. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Sets customized information of PDF document. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)