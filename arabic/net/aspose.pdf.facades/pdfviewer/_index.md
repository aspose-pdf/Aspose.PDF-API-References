---
title: PdfViewer
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لعرض أو طباعة ملف pdf.
type: docs
weight: 2640
url: /ar/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

يمثل فئة لعرض أو طباعة ملف pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | تهيئة جديد[`PdfViewer`](../pdfviewer) الكائن . |
| [PdfViewer](pdfviewer#constructor_1)(Document) | تهيئة جديد[`PdfViewer`](../pdfviewer) الكائن . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كان الملف سيتم طباعته بحجم محسن. إذا كانت صفحة الطباعة خاطئة بدون تحجيم الصفحة. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كان الملف سيتم طباعته باستخدام التدوير التلقائي |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | الحصول على أو تعيين قيمة AutoRotateMode التي تشير إلى اتجاه الدوران |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | الحصول على نوع إحداثيات الصفحة أو تعيينه (مربعات الوسائط / الاقتصاص). يتم استخدام قيمة كروبوكس افتراضيًا. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | الحصول على أو تعيين وضع العرض التقديمي . |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | الحصول على أو تعيين قيمة تشير إلى المحاذاة الأفقية |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | الحصول على عدد الصفحات لملف Pdf الحالي. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | الحصول على أو تعيين كلمة مرور مستند الإدخال. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الصفحة تتم طباعتها كتدرج الرمادي. افتراضيا هو خطأ. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | تعيين أو الحصول على وضع لـ PdfViewer للطباعة كصورة. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | الحصول على أو تعيين اسم المستند في قائمة انتظار الطابعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كان سيتم إنتاج مربع حوار رقم الصفحة عند الطباعة. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | الحصول على نتيجة مهمة الطباعة. إذا كان النجاح لاغيا خلاف ذلك ، كائن الاستثناء. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | الحصول على خيارات التقديم أو تعيينها . |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | الحصول على الدقة أو تعيينها أثناء العرض والطباعة. دقة أعلى ، سرعة أبطأ. القيمة الافتراضية هي 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة التي تشير إلى عامل القياس. القيمة الافتراضية هي 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | يحصل / يحدد استخدام تحويل صفحة pdf إلى ملف png متوسط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | الحصول على أو تعيين قيمة تشير إلى المحاذاة الرأسية |

## طُرق

| اسم | وصف |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | تهيئة الواجهة . |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | تهيئة الواجهة . |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | تهيئة الواجهة . |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | إغلاق الواجهة . |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | إحضار صفحات من ملف pdf الحالي. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | يقوم بفك تشفير صفحة من ملف PDF واحد. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | التخلص من موارد الواجهة . |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | الحصول على إعدادات الصفحة الافتراضية. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | الحصول على إعدادات الطابعة الافتراضية. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | طباعة مستند Pdf باستخدام الطابعة الافتراضية. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | يطبع مستند Pdf بإعدادات الطابعة. سيتناسب حجم صفحة الإخراج مع حجم الصفحة الأولى للمستند. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | يطبع مستند Pdf بالإعدادات. إذا كان حجم المستند غير متوافق مع حجم الصفحة ، فسيقوم pdf.kit بتمديده ليلائم حجم الصفحة. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | يطبع مستند Pdf بمربع حوار الإعداد. اختر طابعة باستخدام مربع الحوار. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | يفتح ويطبع تدفق PDF كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | يفتح ويطبع ملف PDF كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | يفتح ويطبع تدفق Pdf كبير بإعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات من الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | يفتح ويطبع ملف Pdf كبير بإعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات من الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | يفتح ويطبع تدفق Pdf كبير مع إعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف Pdf يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | يفتح ويطبع ملف PDF كبير بإعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف Pdf يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكبر من 3 ميغابايت ، يوصى بهذه الطريقة للحصول على أداء أفضل. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | يحفظ مستند PDF الناتج للدفق . |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | يحفظ مستند PDF الناتج في ملف. |

### أنظر أيضا

* interface [IFacade](../ifacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
