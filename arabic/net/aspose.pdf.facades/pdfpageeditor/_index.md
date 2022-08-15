---
title: PdfPageEditor
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لتحرير صفحة ملف PDF  بما في ذلك تدوير الصفحة وتصغير الصفحة وتحريك الموضع وتغيير حجم الصفحة.
type: docs
weight: 2600
url: /ar/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

يمثل فئة لتحرير صفحة ملف PDF ، بما في ذلك تدوير الصفحة وتصغير الصفحة وتحريك الموضع وتغيير حجم الصفحة.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | مُنشئ فئة PdfPageEditor . |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | مُنشئ فئة PdfPageEditor . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | الحصول على أو تعيين مدة عرض الصفحات . |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية لمحتوى PDF الأصلي على صفحة النتائج ، الافتراضي هو AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | يحتوي جدول التجزئة على رقم الصفحة ودرجة الدوران ، ويمثل المفتاح رقم الصفحة ، وتمثل قيمة المفتاح التدوير بالدرجات. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | الحصول على أو تحديد حجم صفحة ملف الإخراج. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | الحصول على أو تعيين أرقام الصفحات المراد تحريرها. بشكل افتراضي ، سيتم تحرير كل صفحة. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | الحصول على تدوير الصفحات أو تعيينه ، يجب أن يكون التدوير 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | الحصول على أو تحديد مدة تأثير الانتقال. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | الحصول على نمط الانتقال أو تعيينه لاستخدامه عند الانتقال إلى هذه الصفحة من صفحة أخرى أثناء عرض تقديمي . |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية لمحتوى PDF الأصلي على صفحة النتائج ، الافتراضي هو VerticalAlignmentType. أسفل. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | الحصول على أو تعيين معامل التكبير / التصغير. القيمة 1.0 تقابل 100٪ . القيمة الافتراضية هي 1.0.  يوضح المثال التالي كيفية تغيير تكبير / تصغير صفحات المستند. |

## طُرق

| اسم | وصف |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | تطبيق التغييرات التي تم إجراؤها على صفحات المستند. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf. وثيقة مرتبطة بواجهة . |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | إرجاع حجم المربع المحدد في المستند. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | إرجاع تدوير الصفحة المحددة. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | إرجاع العدد الإجمالي للصفحات. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | إرجاع حجم الصفحة للصفحة المحددة. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | لنقل الأصل من (0 ، 0) إلى النقطة التي تم تعيينها. الأصل من اليسار إلى الأسفل والوحدة هي النقطة (1 بوصة = 72 نقطة). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | يحفظ المستند الذي تم تغييره إلى دفق. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | يحفظ المستند الذي تم تغييره إلى ملف. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | الستائر الرأسية |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | الستائر الرأسية |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | مسح من أسفل |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | بريق قطري |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | الصفحة القديمة تتلاشى |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | صندوق داخلي |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | لمعان من اليسار واليمين |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | مسح اليسار واليمين |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | صندوق الصادر |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | يمين يسار يمسح |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | في انقسام أفقي |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | انقسام أفقي للخارج |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | في انقسام عمودي |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | انقسام عمودي للخارج |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | لمعان من أعلى إلى أسفل |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | مسح من أعلى إلى أسفل |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
