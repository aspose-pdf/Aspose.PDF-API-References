---
title: "Class PdfFileInfo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Facades.PdfFileInfo class. Represents a class for accessing meta information of PDF document"
type: docs
weight: 4640
url: /ar/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

يمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class with default values. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initializes new `PdfFileInfo` object on base of the *document*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Gets or sets the Author information of PDF document. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Gets or sets the CreationDate information of PDF document. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Gets or sets the Creator information of PDF document. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in `PdfFileInfo` constructor. In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Returns true if password is needed to open password protected pdf document. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Gets or sets the customized information of PDF document. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Checkes whether the PDF document is encrypted. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Checkes whether the source input is a valid PDF file. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Gets or sets the Keywords information of PDF document. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Gets or sets the ModDate date information of PDF document. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Gets the number of document pages. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in [`PasswordType`](./passwordtype/). Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Gets the Producer information of PDF document. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Gets or sets the Subject information of PDF document. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Gets or sets the Title information of PDF document. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | يستخدم قواعد تحقق صارمة عبر استخدام خاصية [`IsPdfFile`](./ispdffile/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | يمسح جميع معلومات التعريف الوصفية لمستند PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | يقوم بإلغاء تهيئة الكائن. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | يحصل على إعدادات امتيازات مستند PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | يحصل على معلومات مخصصة لمستند PDF باستخدام اسم الخاصية. إذا لم توجد خاصية تطابق الاسم، سيعيد سلسلة فارغة. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | يحصل على ارتفاع الصفحة المحددة. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | يحصل على دوران الصفحة المحددة. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | يحصل على عرض الصفحة المحددة. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | يحصل على الإزاحة الأفقية لمنطقة عرض الصفحة المحددة. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | يحصل على الإزاحة العمودية لمنطقة عرض الصفحة المحددة. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | يحصل على معلومات الإصدار لمستند PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | يحفظ مستند PDF إلى الملف المحدد. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | احفظ مستند PDF المحدث في الملف المحدد. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | يغيّر الخصائص المحددة صراحةً عن طريق ضبط معلومات الملف، وتبقى الخصائص الأخرى كما هي. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | يضبط معلومات مخصصة لمستند PDF. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


