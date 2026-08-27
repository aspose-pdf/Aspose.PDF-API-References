---
title: "الفئة PdfViewer"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfViewer. تمثل فئة لعرض أو طباعة ملف pdf"
type: docs
weight: 4750
url: /ar/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

يمثل فئة لعرض أو طباعة ملف pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | يُهيئ كائنًا جديدًا من `PdfViewer`. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | يُهيئ كائنًا جديدًا من `PdfViewer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بحجم مُحسّن. إذا كانت false تُطبع الصفحة دون تعديل الحجم. إذا كانت true تُطبع الصفحة مع تعديل الحجم لتناسب المنطقة القابلة للطباعة. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف مع تدوير تلقائي. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | يحصل أو يعيّن قيمة AutoRotateMode التي تشير إلى اتجاه التدوير. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | يحصل أو يعيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox كإعداد افتراضي. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى المحاذاة الأفقية. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | يحصل على عدد صفحات ملف Pdf الحالي. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | يحصل أو يعيّن كلمة مرور المستند الإدخالية. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بتدرج الرمادي. القيمة الافتراضية هي false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | يعيّن أو يحصل على وضع لطباعة PdfViewer كصورة. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | يحصل أو يعيّن اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يُظهر حوار رقم الصفحة عند الطباعة. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | يحصل على نتيجة مهمة الطباعة. إذا نجحت تكون النتيجة null؛ وإلا يكون كائن الاستثناء. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | يحصل أو يعيّن الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | يحصل أو يعيّن قيمة عددية عائمة تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | يحصل/يعيّن استخدام تحويل صفحة pdf إلى ملف png وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى المحاذاة العمودية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | يُهيئ الواجهة. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | يُهيئ الواجهة. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | يُهيئ الواجهة. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | يغلق الواجهة. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | احصل على صفحات ملف pdf الحالي. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | يفكّ شفرة صفحة من ملف Pdf واحد. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | يتخلص من موارد الواجهة. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | يحصل على إعدادات Page الافتراضية. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | يحصل على إعدادات الطابعة الافتراضية. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | يطبع مستند Pdf باستخدام الطابعة الافتراضية. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | يطبع مستند Pdf باستخدام إعدادات الطابعة. سيتناسب حجم صفحة الإخراج مع حجم الصفحة الأولى للمستند. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | يطبع مستند Pdf باستخدام الإعدادات. إذا لم يتطابق حجم المستند مع حجم Page، سيتم توسيعه ليتناسب مع حجم Page. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | يطبع مستند Pdf باستخدام حوار الإعداد. اختر طابعة باستخدام الحوار. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | يفتح ويطبع تدفق Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | يفتح ويطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | يفتح ويطبع تدفق Pdf كبير باستخدام إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | يفتح ويطبع ملف Pdf كبير باستخدام إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | يفتح ويطبع تدفق Pdf كبير باستخدام إعدادات Page وإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | يفتح ويطبع ملف Pdf كبير باستخدام إعدادات Page وإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | يحفظ مستند PDF الناتج إلى تدفق. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | يحفظ مستند PDF الناتج إلى ملف. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments)(params Document[]) | يطبع عدة مستندات PDF باستخدام الطابعة الافتراضية وإعدادات Page. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_7)(params Stream[]) | يطبع عدة مستندات PDF من التدفقات المقدمة باستخدام الطابعة الافتراضية وإعدادات Page. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_8)(params string[]) | يطبع عدة مستندات PDF باستخدام الطابعة الافتراضية وإعدادات Page. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_1)(PrinterSettings, params Document[]) | يطبع عدة مستندات PDF باستخدام إعدادات الطابعة المحددة. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_5)(PrinterSettings, params Stream[]) | يطبع مستندات PDF متعددة من التدفقات المقدمة باستخدام إعدادات الطابعة المحددة. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_6)(PrinterSettings, params string[]) | يطبع عدة مستندات PDF باستخدام إعدادات الطابعة المحددة. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_2)(PrinterSettings, PageSettings, params Document[]) | يطبع مستندات PDF متعددة باستخدام الطابعة وإعدادات الصفحة المحددة. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_3)(PrinterSettings, PageSettings, params Stream[]) | يطبع مستندات PDF متعددة من التدفقات المقدمة باستخدام الطابعة وإعدادات الصفحة المحددة. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_4)(PrinterSettings, PageSettings, params string[]) | يطبع مستندات PDF متعددة باستخدام الطابعة وإعدادات الصفحة المحددة. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | يحدث قبل بدء الطباعة ويسمح بتوفير معالجات طباعة مخصصة بدلاً من المعالج الافتراضي. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | يحدث عندما تنتهي طباعة صفحة في PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | يحدث قبل أن تبدأ صفحة في الطباعة. |

### انظر أيضًا

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


