---
title: "الفئة PdfFileStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileStamp. فئة لإضافة العلامات المائية أو الخلفية إلى ملفات PDF."
type: docs
weight: 4690
url: /ar/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | يُهيئ كائن `PdfFileStamp` جديد على أساس *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بتنسيق PDF الافتراضي دون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | يحصل أو يعيّن نمط ترقيم الصفحات. القيم الممكنة: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | يحصل أو يعيّن علامة التحسين. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. يسمح ذلك بتقليل حجم الملف الناتج لكنه قد يسبب تنفيذًا أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | يحصل على ارتفاع الصفحة الأولى في ملف المصدر. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | يحصل أو يعيّن دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية: 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | يحصل على عرض الصفحة الأولى في ملف الإدخال. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | معرّف الطابع للعلامة التالية المضافة (بما في ذلك رؤوس/تذييلات الصفحات/أرقام الصفحات). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | يحصل أو يعيّن الرقم الابتدائي للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. على سبيل المثال إذا تم تعيين StartingNumber إلى 100، ستحصل صفحات المستند على الأرقام 100، 101، 102... |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | يضيف تذييلًا إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | يضيف صورة ك تذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | يضيف صورة ك تذييل إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | يضيف تذييلًا إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | يضيف صورة ك تذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | يضيف صورة ك تذييل للصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | يضيف رأسًا إلى الصفحة. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | يضيف صورة ك رأس على الصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | يضيف صورة ك رأس إلى صفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | يضيف رأسًا إلى صفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | يضيف صورة في أعلى الصفحة. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | يضيف صورة ك رأس على الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | يضيف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | يضيف طابعًا إلى الملف. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | يغلق الملفات المفتوحة ويحفظ التغييرات. تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج فلن يتم إغلاقها بواسطة طريقة Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | يحفظ المستند في التدفق المحدد. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | يحفظ النتيجة في الملف المحدد. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | الموضع السفلي الأيسر. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | الموضع السفلي الأوسط. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | الموضع السفلي الأيمن. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | الموضع الأيسر. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | الموضع الأيمن. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | الموضع العلوي الأيسر. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | الموضع العلوي الأوسط. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | الموضع العلوي الأيمن. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


