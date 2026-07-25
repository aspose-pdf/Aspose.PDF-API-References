---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لعرض أو طباعة ملف pdf."
type: docs
weight: 610
url: /ar/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

يمثل فئة لعرض أو طباعة ملف pdf.

## الحقول

| حقل | الوصف |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfViewer](#PdfViewer--) | يُهيئ كائن {@code PdfViewer} جديد. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | يُهيئ كائن {@code PdfViewer} جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.io.InputStream-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.lang.String-) | ينشئ الواجهة. |
| [close](#close--) | يغلق ملف Pdf الحالي. |
| [closePdfFile](#closePdfFile--) | يغلق ملف Pdf الحالي. |
| [decodeAllPages](#decodeAllPages--) | احصل على صفحات ملف pdf الحالي. |
| [decodePage](#decodePage-int-) | يفك شفرة صفحة من ملف Pdf واحد. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | يفك شفرة الصفحة إلى BufferedImage |
| [dispose](#dispose--) | يحرّر موارد الواجهة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [getAutoResize](#getAutoResize--) | يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بحجم مُحسّن. |
| [getAutoRotate](#getAutoRotate--) | يحصل على قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف مع التدوير التلقائي |
| [getAutoRotateMode](#getAutoRotateMode--) | يحصل على قيمة AutoRotateMode تشير إلى اتجاه التدوير |
| [getCoordinateType](#getCoordinateType--) | يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [getCopiesPrinted](#getCopiesPrinted--) | يحصل على عدد النسخ المطبوعة |
| [getDefaultPageSettings](#getDefaultPageSettings--) | يحصل على إعدادات الصفحة الافتراضية. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | يحصل على إعدادات الطابعة الافتراضية. |
| [getFormPresentationMode](#getFormPresentationMode--) | يحصل على وضع عرض النموذج. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على قيمة تشير إلى المحاذاة الأفقية |
| [getPageCount](#getPageCount--) | يحصل على عدد صفحات ملف Pdf الحالي. |
| [getPassword](#getPassword--) | يحصل على كلمة مرور المستند المدخل. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بتدرج الرمادي. القيمة الافتراضية هي false. </p> <hr> القيمة الافتراضية false هي false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> يحصل على وضع لـ PdfViewer للطباعة كصورة. </p> |
| [getPrinterJobName](#getPrinterJobName--) | يحصل على اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| [getPrintPageDialog](#getPrintPageDialog--) | يحصل على قيمة منطقية تشير إلى ما إذا كان يتم إظهار حوار رقم الصفحة عند الطباعة. |
| [getPrintStatus](#getPrintStatus--) | يحصل على نتيجة مهمة الطباعة. إذا نجحت تكون النتيجة null؛ وإلا يكون كائن الاستثناء. |
| [getRenderingOptions](#getRenderingOptions--) | يحصل على خيارات العرض. |
| [getResolution](#getResolution--) | يحصل أو يضبط الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. هذه الخاصية تغير دقة الصورة في تدفقات تحويل الصفحة إلى صورة: عندما يتم تعيين {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) إلى {@code }, أو عندما يتم استدعاء طريقة {@link #decodePage(int)} أو {@link #decodeAllPages}. لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) في فئة {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | يحصل على قيمة نقطية تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | يحصل على استخدام تحويل صفحة pdf إلى ملف png وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على قيمة تشير إلى المحاذاة العمودية |
| [isShowHiddenAreas](#isShowHiddenAreas--) | هذه الطريقة مهجورة. يحصل على علم يتحكم في رؤية المناطق المخفية على الصفحة. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> يفتح تدفق ملف Pdf. لكنه لا يقوم فعليًا بفك ترميز صفحات ملف Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> يفتح ملف Pdf، لكنه لا يقوم فعليًا بفك ترميز صفحات ملف Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> يطبع مستند Pdf باستخدام الطابعة الافتراضية. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يطبع مستند Pdf باستخدام إعدادات الطابعة. سيتناسب حجم الصفحة الناتج مع حجم الصفحة الأولى للمستند. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يطبع مستند Pdf بالإعدادات. إذا لم يكن حجم المستند متوافقًا مع حجم الصفحة، سيقوم pdf.kit بتمديده ليتناسب مع حجم الصفحة. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> يفتح ويطبع تدفق Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> تم دمج فتح وطباعة الملف في هذه الطريقة ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يفتح ويطبع تدفق Pdf كبير مع إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> تم دمج فتح وطباعة الملف في هذه الطريقة ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يفتح ويطبع تدفق Pdf كبير مع إعدادات صفحة وإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> تم دمج فتح وطباعة الملف في هذه الطريقة ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> يفتح ويطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يفتح ويطبع ملف PDF كبير بإعدادات طابعة محددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> هذه الطريقة مدمجة بين فتح الملف وطباعة الملف ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> يفتح ويطبع ملف PDF كبير بإعدادات صفحة وطابعة محددة. إذا كان ملف PDF الخاص بك يحتوي على مئات الصفحات أو أكثر أو حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> هذه الطريقة مدمجة بين فتح الملف وطباعة الملف ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً. |
| [save](#save-java.io.InputStream-) | يحفظ مستند PDF الناتج إلى تدفق. |
| [save](#save-java.lang.String-) | يحفظ مستند PDF الناتج إلى ملف. |
| [setAutoResize](#setAutoResize-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بحجم مُحسّن. |
| [setAutoRotate](#setAutoRotate-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بتدوير تلقائي |
| [setAutoRotateMode](#setAutoRotateMode-int-) | يضبط قيمة AutoRotateMode التي تشير إلى اتجاه التدوير |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | يضبط وضع عرض النموذج. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط قيمة تشير إلى المحاذاة الأفقية |
| [setPassword](#setPassword-java.lang.String-) | يضبط كلمة مرور المستند المدخل. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بتدرج الرمادي. القيمة الافتراضية هي false. </p> <hr> القيمة الافتراضية false هي false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> يضبط وضعًا لـ PdfViewer للطباعة كصورة. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | يضبط اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كان يجب إظهار حوار رقم الصفحة عند الطباعة. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | يضبط خيارات العرض. |
| [setResolution](#setResolution-int-) | يضبط الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. هذه الخاصية تغير دقة الصورة في عمليات تحويل الصفحة إلى صورة: عندما يكون {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) مضبوطًا على {@code }, أو عندما يتم استدعاء طريقة {@link #decodePage(int)} أو {@link #decodeAllPages}. لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) في فئة {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | يضبط قيمة عددية ذات نقطة عائمة تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | مهمل. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | يضبط استخدام تحويل صفحة PDF إلى ملف PNG وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط قيمة تشير إلى المحاذاة العمودية |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

يضيف/يزيل الاشتراك في حدث طباعة الصفحة الأخيرة.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

يُهيئ كائن {@code PdfViewer} جديد.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
يُهيئ كائن {@code PdfViewer} جديد.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.io.InputStream-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.lang.String-}
ينشئ الواجهة.

### close {#close--}
```
public void close()
```

يغلق ملف Pdf الحالي.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

يغلق ملف Pdf الحالي.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

احصل على صفحات ملف pdf الحالي.

**Returns:**
إرجاع مصفوفة من صور صفحات PDF.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

يفك شفرة صفحة من ملف Pdf واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة في ملف PDF واحد والذي يجب أن يكون بين 1 و PageCount. |

**Returns:**
إرجاع صورة صفحة PDF.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
يفك شفرة الصفحة إلى BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يحرّر موارد الواجهة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بحجم مُحسّن.

**Returns:**
قيمة منطقية: إذا كانت false اطبع الصفحة بدون تعديل الحجم. إذا كانت true اطبع الصفحة مع تعديل الحجم لتناسب المنطقة القابلة للطباعة.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

يحصل على قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف مع التدوير التلقائي

**Returns:**
قيمة منطقية

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

يحصل على قيمة AutoRotateMode تشير إلى اتجاه التدوير

**Returns:**
عنصر AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

**Returns:**
عنصر PageCoordinateType @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

يحصل على عدد النسخ المطبوعة

**Returns:**
قيمة int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

يحصل على إعدادات الصفحة الافتراضية.

**Returns:**
كائن إعدادات الصفحة.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

يحصل على إعدادات الطابعة الافتراضية.

**Returns:**
كائن إعدادات الصفحة.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

يحصل على وضع عرض النموذج.

**Returns:**
عنصر FormPresentationMode @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على قيمة تشير إلى المحاذاة الأفقية

**Returns:**
عنصر HorizontalAlignment @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

يحصل على عدد صفحات ملف Pdf الحالي.

**Returns:**
إرجاع عدد الصفحات.

### getPassword {#getPassword--}
```
public String getPassword()
```

يحصل على كلمة مرور المستند المدخل.

**Returns:**
قيمة سلسلة

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بتدرج الرمادي. القيمة الافتراضية هي false. </p> <hr> القيمة الافتراضية false هي false.

**Returns:**
قيمة منطقية

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> يحصل على وضع لـ PdfViewer للطباعة كصورة. </p>

**Returns:**
قيمة منطقية <hr> إذا كانت true يطبع دائمًا كصورة (ينتج صورة تُطبع) إذا كانت false يطبع مباشرة إلى الجهاز إذا كانت جميع الميزات مدعومة. في حالة احتواء المستند على ميزات غير مدعومة قد يقرر النظام تلقائيًا الطباعة كصورة. القيمة الافتراضية هي false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

يحصل على اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف.

**Returns:**
قيمة سلسلة

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

يحصل على قيمة منطقية تشير إلى ما إذا كان يتم إظهار حوار رقم الصفحة عند الطباعة.

**Returns:**
قيمة منطقية

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

يحصل على نتيجة مهمة الطباعة. إذا نجحت تكون النتيجة null؛ وإلا يكون كائن الاستثناء.

**Returns:**
كائن استثناء أو null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

يحصل على خيارات العرض.

**Returns:**
كائن RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

يحصل أو يضبط الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. هذه الخاصية تغير دقة الصورة في تدفقات تحويل الصفحة إلى صورة: عندما يتم تعيين {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) إلى {@code }, أو عندما يتم استدعاء طريقة {@link #decodePage(int)} أو {@link #decodeAllPages}. لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) في فئة {@code PageSettings}.

**Returns:**
قيمة int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

يحصل على قيمة نقطية تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0.

**Returns:**
قيمة عددية عائمة.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

يحصل على استخدام تحويل صفحة pdf إلى ملف png وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا.

**Returns:**
قيمة منطقية.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل على قيمة تشير إلى المحاذاة العمودية

**Returns:**
عنصر VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

هذه الطريقة مهجورة. يحصل على علم يتحكم في رؤية المناطق المخفية على الصفحة.

**Returns:**
قيمة منطقية

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> يفتح تدفق ملف Pdf. لكنه لا يقوم فعليًا بفك تشفير صفحات ملف Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream(\"d:\\\\test.pdf\"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> يفتح ملف Pdf، لكنه لا يقوم فعليًا بفك تشفير صفحات ملف Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> يطبع مستند Pdf باستخدام الطابعة الافتراضية. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يطبع مستند Pdf باستخدام إعدادات الطابعة. سيتطابق حجم صفحة الإخراج مع حجم الصفحة الأولى للمستند. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يطبع مستند Pdf باستخدام الإعدادات. إذا لم يكن حجم المستند متوافقًا مع حجم الصفحة، سيقوم pdf.kit بتمديده ليتناسب مع حجم الصفحة. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize(\"A4\", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> يفتح ويطبع تدفق Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@\"d:\\test.pdf\"))); viewer.closePdfFile(); </pre> <hr> تم دمج فتح وطباعة الملف في هذه الطريقة ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يفتح ويطبع تدفق Pdf كبير باستخدام إعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"), ps); viewer.closePdfFile(); </pre> <hr> تم دمج فتح وطباعة الملف في هذه الطريقة ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يفتح ويطبع تدفق Pdf كبير مع إعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> لقد دمجت هذه الطريقة عملية الفتح والطباعة للملف ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> يفتح ويطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يفتح ويطبع ملف Pdf كبير مع إعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> لقد دمجت هذه الطريقة عملية الفتح والطباعة للملف ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> يفتح ويطبع ملف Pdf كبير مع إعدادات الصفحة وإعدادات الطابعة المحددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> لقد دمجت هذه الطريقة عملية الفتح والطباعة للملف ولا تحتاج إلى استدعاء OpenPdfFile() صراحةً.

### save {#save-java.io.InputStream-}
يحفظ مستند PDF الناتج إلى تدفق.

### save {#save-java.lang.String-}
يحفظ مستند PDF الناتج إلى ملف.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بحجم مُحسّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية: إذا كانت false اطبع الصفحة بدون تعديل الحجم. إذا كانت true اطبع الصفحة مع تعديل الحجم لتناسب المنطقة القابلة للطباعة. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كان يجب طباعة الملف بتدوير تلقائي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

يضبط قيمة AutoRotateMode التي تشير إلى اتجاه التدوير

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

يضبط وضع عرض النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر FormPresentationMode |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط قيمة تشير إلى المحاذاة الأفقية

### setPassword {#setPassword-java.lang.String-}
يضبط كلمة مرور المستند المدخل.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بتدرج الرمادي. القيمة الافتراضية هي false. </p> <hr> القيمة الافتراضية false هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> يضبط وضعًا لـ PdfViewer للطباعة كصورة. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية <hr> إذا كانت true يطبع دائمًا كصورة (ينتج صورة تُطبع) إذا كانت false يطبع مباشرة إلى الجهاز إذا كانت جميع الميزات مدعومة. في حالة احتواء المستند على ميزات غير مدعومة قد يقرر النظام تلقائيًا الطباعة كصورة. القيمة الافتراضية هي false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
يضبط اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كان يجب إظهار حوار رقم الصفحة عند الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
يضبط خيارات العرض.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

يضبط الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. هذه الخاصية تغير دقة الصورة في عمليات تحويل الصفحة إلى صورة: عندما يكون {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) مضبوطًا على {@code }, أو عندما يتم استدعاء طريقة {@link #decodePage(int)} أو {@link #decodeAllPages}. لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) في فئة {@code PageSettings}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

يضبط قيمة عددية ذات نقطة عائمة تشير إلى عامل المقياس. القيمة الافتراضية هي 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عددية عائمة. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

مهمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

يضبط استخدام تحويل صفحة PDF إلى ملف PNG وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط قيمة تشير إلى المحاذاة العمودية
