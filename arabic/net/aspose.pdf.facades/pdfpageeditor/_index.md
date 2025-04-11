---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfPageEditor. تمثل فئة لتحرير صفحات ملفات PDF بما في ذلك تدوير الصفحة، تكبير الصفحة، تغيير موضع الصفحة وتغيير حجم الصفحة
type: docs
weight: 4590
url: /ar/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

تمثل فئة لتحرير صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، تغيير الموضع وتغيير حجم الصفحة.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | مُنشئ لفئة PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | مُنشئ لفئة PdfPageEditor. |

## Properties

| Name | Description |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | يحصل أو يحدد مدة العرض للصفحات. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة الوثيقة التي يعمل عليها. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية لمحتوى PDF الأصلي على الصفحة الناتجة، القيمة الافتراضية هي AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | جدول يحتوي على رقم الصفحة ودرجة التدوير، المفتاح يمثل رقم الصفحة، والقيمة تمثل التدوير بالدرجات. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | يحصل أو يحدد حجم صفحة الملف الناتج. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | يحصل أو يحدد أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | يحصل أو يحدد تدوير الصفحات، يجب أن يكون التدوير 0، 90، 180 أو 270. القيمة الافتراضية هي 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | يحصل أو يحدد مدة تأثير الانتقال. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | يحصل أو يحدد نمط الانتقال الذي سيتم استخدامه عند الانتقال إلى هذه الصفحة من صفحة أخرى أثناء العرض. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية لمحتوى PDF الأصلي على الصفحة الناتجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | يحصل أو يحدد معامل التكبير. القيمة 1.0 تتوافق مع 100%. القيمة الافتراضية هي 1.0. المثال التالي يوضح كيفية تغيير تكبير صفحات الوثيقة. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | يطبق التغييرات التي تم إجراؤها على صفحات الوثيقة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يتخلص من Aspose.Pdf.Document المرتبطة بواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | يعيد حجم الصندوق المحدد في الوثيقة. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | يعيد تدوير الصفحة المحددة. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | يعيد العدد الإجمالي للصفحات. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | يعيد حجم الصفحة للصفحة المحددة. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | ينقل الأصل من (0، 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي نقطة (1 بوصة = 72 نقطة). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | يحفظ الوثيقة المعدلة في التدفق. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | يحفظ الوثيقة المعدلة في الملف. |

## Fields

| Name | Description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | الستائر الرأسية |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | الستائر الرأسية |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | مسح من الأسفل إلى الأعلى |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | بريق قطري |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | الصفحة القديمة تذوب |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | صندوق داخلي |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | بريق من اليسار إلى اليمين |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | مسح من اليسار إلى اليمين |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | صندوق خارجي |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | مسح من اليمين إلى اليسار |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | انقسام أفقي داخلي |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | انقسام أفقي خارجي |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | انقسام عمودي داخلي |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | انقسام عمودي خارجي |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | بريق من الأعلى إلى الأسفل |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | مسح من الأعلى إلى الأسفل |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)