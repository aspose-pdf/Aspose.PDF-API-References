---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileStamp. فئة لإضافة طوابع أو علامات مائية أو خلفيات إلى ملفات PDF
type: docs
weight: 4570
url: /ar/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

فئة لإضافة طوابع (علامات مائية أو خلفيات) إلى ملفات PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | مُنشئ فئة PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfFileStamp` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ ملف النتيجة بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بالتنسيق الافتراضي لـ PDF دون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | يحتفظ بالأمان إذا كانت القيمة صحيحة. (ستتم تنفيذ هذه الميزة في الإصدارات القادمة). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | يحصل على أو يحدد نمط ترقيم الصفحات. القيم الممكنة: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | يحصل على أو يحدد علامة تحسين. يتم دمج تدفقات الموارد المتساوية في ملف النتيجة في كائن PDF واحد إذا تم تعيين هذه العلامة. هذا يسمح بتقليل حجم الملف الناتج ولكنه قد يتسبب في تنفيذ أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | يحصل على ارتفاع الصفحة الأولى في ملف المصدر. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | يحصل على أو يحدد دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | يحصل على عرض الصفحة الأولى في ملف الإدخال. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | معرف الطابع الخاص بالطابع المضاف التالي (بما في ذلك رؤوس الصفحات/تذييلات الصفحات/أرقام الصفحات). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | يحصل على أو يحدد الرقم الابتدائي للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. على سبيل المثال، إذا تم تعيين StartingNumber على 100، فستكون أرقام صفحات المستند 100، 101، 102... |

## Methods

| Name | Description |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | يضيف تذييلًا إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | يضيف صورة كتذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | يضيف صورة كتذييل إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | يضيف تذييلًا إلى صفحات المستند. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | يضيف صورة كتذييل للصفحة. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | يضيف صورة كتذييل للصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | يضيف رأسًا إلى الصفحة. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | يضيف صورة كرأس على الصفحات. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | يضيف صورة كرأس إلى صفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | يضيف رأسًا إلى صفحات الملف. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | يضيف صورة في أعلى الصفحة. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | يضيف صورة كرأس على الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركزيًا أفقيًا. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | يضيف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركزيًا أفقيًا. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | يضيف رقم الصفحة إلى الصفحات. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | يضيف رقم الصفحة إلى صفحات المستند. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | يضيف طابعًا إلى الملف. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | يغلق الملفات المفتوحة ويحفظ التغييرات. تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج، فلن يتم إغلاقها بواسطة طريقة Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | يحفظ المستند في التدفق المحدد. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | يحفظ النتيجة في الملف المحدد. |

## Fields

| Name | Description |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | الموضع السفلي الأيسر. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | الموضع السفلي الأوسط. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | الموضع السفلي الأيمن. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | الموضع الأيسر. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | الموضع الأيمن. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | الموضع العلوي الأيسر. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | الموضع العلوي الأوسط. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | الموضع العلوي الأيمن. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)