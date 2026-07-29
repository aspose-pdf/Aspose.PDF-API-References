---
title: "الفئة PdfPageEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfPageEditor. تمثل فئة لتعديل صفحات ملفات PDF بما في ذلك تدوير الصفحة وتكبيرها وتحريك موقعها وتغيير حجم الصفحة."
type: docs
weight: 4710
url: /ar/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

يمثل فئة لتحرير صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموقع وتغيير حجم الصفحة.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | منشئ لفئة PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | منشئ لفئة PdfPageEditor. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | يحصل أو يضبط مدة العرض للصفحات. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | يحصل أو يضبط محاذاة المحتوى الأصلي PDF أفقياً على الصفحة الناتجة، الافتراضي هو AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | جدول تجزئة يحتوي على رقم الصفحة ودرجة الدوران، المفتاح يمثل رقم الصفحة، قيمة المفتاح تمثل درجة الدوران بالدرجات. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | يحصل أو يضبط حجم صفحة ملف الإخراج. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | يحصل أو يضبط أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | يحصل أو يعيّن دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | يحصل أو يعيّن مدة تأثير الانتقال. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | يحصل أو يعيّن نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | يحصل أو يعيّن المحاذاة العمودية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | يحصل أو يعيّن معامل التكبير. القيمة 1.0 تعادل 100٪. القيمة الافتراضية هي 1.0. المثال التالي يوضح كيفية تغيير تكبير صفحات المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | تطبيق التغييرات التي تم إجراؤها على صفحات المستند. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يفرغ Aspose.Pdf.Document المرتبط بواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | يعيد حجم الصندوق المحدد في المستند. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | يعيد دوران الصفحة المحددة. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | يعيد العدد الإجمالي للصفحات. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | يعيد حجم الصفحة للصفحة المحددة. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | ينقل الأصل من (0, 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي النقطة (1 بوصة = 72 نقطة). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | يحفظ المستند المعدل إلى تدفق. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | يحفظ المستند المعدل إلى ملف. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | ستائر عمودية |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | ستائر عمودية |
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
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | In Vertical Split |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Out Vertical Split |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Top-Bottom Glitter |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Top-Bottom Wipe |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


