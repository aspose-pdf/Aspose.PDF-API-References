---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer class. يمثل فئة لعرض أو طباعة ملف PDF
type: docs
weight: 4630
url: /ar/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

يمثل فئة لعرض أو طباعة ملف PDF.

```csharp
public sealed class PdfViewer : IFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | يقوم بتهيئة كائن `PdfViewer` جديد. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfViewer` جديد. |

## Properties

| Name | Description |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كان يجب طباعة الملف بحجم محسن. إذا كانت القيمة خاطئة، تتم طباعة الصفحة بدون تغيير حجم الصفحة. إذا كانت القيمة صحيحة، تتم طباعة الصفحة مع تغيير الحجم لتناسب المنطقة القابلة للطباعة. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كان يجب طباعة الملف مع التدوير التلقائي |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | يحصل أو يحدد قيمة AutoRotateMode التي تشير إلى اتجاه التدوير |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (صناديق الوسائط/القص). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع تقديم النموذج. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | يحصل أو يحدد قيمة تشير إلى المحاذاة الأفقية |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | يحصل على عدد صفحات ملف PDF الحالي. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | يحصل أو يحدد كلمة مرور مستند الإدخال. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الصفحة تتم طباعتها بالأبيض والأسود. القيمة الافتراضية هي خاطئة. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | يحدد أو يحصل على وضع لطباعة PdfViewer كصورة. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | يحصل أو يحدد اسم المستند في قائمة انتظار الطابعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كان يجب عرض مربع حوار رقم الصفحة عند الطباعة. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | يحصل على نتيجة عملية الطباعة. إذا كانت ناجحة، تكون القيمة null؛ خلاف ذلك، كائن استثناء. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | يحصل أو يحدد الدقة أثناء العرض والطباعة. كلما زادت الدقة، كانت السرعة أبطأ. القيمة الافتراضية هي 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | يحصل أو يحدد قيمة نقطة عائمة تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | يحصل/يحدد استخدام تحويل صفحة PDF إلى ملف PNG وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم الملف الناتج مهمًا. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | يحصل أو يحدد قيمة تشير إلى المحاذاة الرأسية |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | يقوم بتهيئة الواجهة. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | يقوم بتهيئة الواجهة. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | يقوم بتهيئة الواجهة. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | يغلق الواجهة. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | يحصل على صفحات ملف PDF الحالي. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | يقوم بفك تشفير صفحة من ملف PDF واحد. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | يتخلص من موارد الواجهة. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | يحصل على إعدادات الصفحة الافتراضية. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | يحصل على إعدادات الطابعة الافتراضية. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | يطبع مستند PDF باستخدام الطابعة الافتراضية. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | يطبع مستند PDF مع إعدادات الطابعة. سيكون حجم الصفحة الناتجة متناسبًا مع حجم الصفحة الأولى من المستند. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | يطبع مستند PDF مع الإعدادات. إذا لم يتوافق حجم المستند مع حجم الصفحة، سيتم تمديده ليتناسب مع حجم الصفحة. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | يطبع مستند PDF مع مربع حوار الإعداد. اختر طابعة باستخدام الحوار. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | يفتح ويطبع تدفق PDF كبير. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | يفتح ويطبع ملف PDF كبير. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | يفتح ويطبع تدفق PDF كبير مع إعدادات الطابعة المحددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | يفتح ويطبع ملف PDF كبير مع إعدادات الطابعة المحددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | يفتح ويطبع تدفق PDF كبير مع إعدادات الصفحة وإعدادات الطابعة المحددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | يفتح ويطبع ملف PDF كبير مع إعدادات الصفحة وإعدادات الطابعة المحددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميجابايت، يُوصى باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | يحفظ مستند PDF الناتج إلى التدفق. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | يحفظ مستند PDF الناتج إلى ملف. |

## Events

| Name | Description |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | يحدث قبل بدء الطباعة ويسمح بتوفير معالجات طباعة مخصصة بدلاً من المعالج الافتراضي. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | يحدث عندما تنتهي طباعة صفحة في PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | يحدث قبل بدء طباعة صفحة. |

### See Also

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)