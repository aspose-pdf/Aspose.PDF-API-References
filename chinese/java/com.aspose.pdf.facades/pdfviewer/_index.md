---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于查看或打印 PDF 的类。"
type: docs
weight: 610
url: /zh/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

表示用于查看或打印 PDF 的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | 在最后一页打印事件上添加/移除订阅。 |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | 在最后一页打印事件上添加/移除订阅。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfViewer](#PdfViewer--) | 初始化新的 {@code PdfViewer} 对象。 |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | 初始化新的 {@code PdfViewer} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-) | 初始化 facade。 |
| [close](#close--) | 关闭当前的 Pdf 文件。 |
| [closePdfFile](#closePdfFile--) | 关闭当前的 Pdf 文件。 |
| [decodeAllPages](#decodeAllPages--) | 获取当前 pdf 文件的页面。 |
| [decodePage](#decodePage-int-) | 解码单个 Pdf 文件的页面。 |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | 将页面解码为 BufferedImage |
| [dispose](#dispose--) | 释放外观资源。此方法已过时，请改用 close()。 |
| [getAutoResize](#getAutoResize--) | 设置一个布尔值，指示文件是否以优化尺寸打印。 |
| [getAutoRotate](#getAutoRotate--) | 获取一个布尔值，指示文件是否自动旋转打印。 |
| [getAutoRotateMode](#getAutoRotateMode--) | 获取 AutoRotateMode 值，指示旋转方向。 |
| [getCoordinateType](#getCoordinateType--) | 获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [getCopiesPrinted](#getCopiesPrinted--) | 获取已打印的副本数 |
| [getDefaultPageSettings](#getDefaultPageSettings--) | 获取默认页面设置。 |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | 获取默认打印机设置。 |
| [getFormPresentationMode](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取指示水平对齐方式的值 |
| [getPageCount](#getPageCount--) | 获取当前 Pdf 文件的页数。 |
| [getPassword](#getPassword--) | 获取输入文档密码。 |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 </p> <hr> 默认 false。 |
| [getPrintAsImage](#getPrintAsImage--) | <p> 获取 PdfViewer 以图像方式打印的模式。 </p> |
| [getPrinterJobName](#getPrinterJobName--) | 获取文档打印时在打印队列中的名称。默认值为文件名。 |
| [getPrintPageDialog](#getPrintPageDialog--) | 获取一个布尔值，指示打印时是否生成页码对话框。 |
| [getPrintStatus](#getPrintStatus--) | 获取打印作业的结果。如果成功则为 null；否则为异常对象。 |
| [getRenderingOptions](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution](#getResolution--) | 获取或设置查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。此属性在页面转图像的转换流程中更改图像分辨率：当 {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) 被设置为 {@code }，或调用 {@link #decodePage(int)} 或 {@link #decodeAllPages} 方法时。要为直接打印到打印机设置打印机分辨率，请使用 {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) 属性，位于 {@code PageSettings} 类中。 |
| [getScaleFactor](#getScaleFactor--) | 获取指示缩放因子的浮点值。默认值为 1.0。 |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | 获取在文件模式下打印时将 pdf 页面转换为中间 png 文件的使用情况。当输出文件大小很重要时使用它。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取指示垂直对齐方式的值 |
| [isShowHiddenAreas](#isShowHiddenAreas--) | 此方法已弃用，获取控制页面隐藏区域可见性的标志。 |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> 打开一个 Pdf 文件流。但并未实际解码该 Pdf 文件的页面。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> 打开一个 Pdf 文件，但并未实际解码该 Pdf 文件的页面。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> 使用默认打印机打印 Pdf 文档。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 使用打印机设置打印 Pdf 文档。输出页面尺寸将适配文档的首页尺寸。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 使用设置打印 Pdf 文档。如果文档尺寸与页面尺寸不兼容，pdf.kit 将扩展文档以适配页面尺寸。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> 打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。 |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 打开并使用指定的打印机设置打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。 |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 打开并使用指定的页面设置和打印机设置打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。 |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> 打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 打开并使用指定的打印机设置打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。 |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 打开并打印具有指定页面设置和打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百页甚至更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，无需显式调用 OpenPdfFile()。 |
| [save](#save-java.io.InputStream-) | 将结果 PDF 文档保存到流中。 |
| [save](#save-java.lang.String-) | 将结果 PDF 文档保存到文件中。 |
| [setAutoResize](#setAutoResize-boolean-) | 设置一个布尔值，指示文件是否以优化尺寸打印。 |
| [setAutoRotate](#setAutoRotate-boolean-) | 设置一个布尔值，指示文件是否使用自动旋转打印。 |
| [setAutoRotateMode](#setAutoRotateMode-int-) | 设置 AutoRotateMode 值，指示旋转方向。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | 设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置一个值，指示水平对齐方式。 |
| [setPassword](#setPassword-java.lang.String-) | 设置输入文档的密码。 |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 </p> <hr> 默认 false。 |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> 为 PdfViewer 设置以图像方式打印的模式。 </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | 设置文档在打印队列中的名称。默认值为文件名。 |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | 设置一个布尔值，指示打印时是否生成页码对话框。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setResolution](#setResolution-int-) | 设置查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。此属性会在页面转图像的转换流程中更改图像分辨率：当 {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) 被设置为 {@code }，或调用 {@link #decodePage(int)} 或 {@link #decodeAllPages} 方法时。若要为直接打印到打印机设置打印机分辨率，请使用 {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) 属性，位于 {@code PageSettings} 类中。 |
| [setScaleFactor](#setScaleFactor-float-) | 设置一个浮点值，指示缩放因子。默认值为 1.0。 |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | 已弃用。 |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | 设置在文件模式下打印时将 pdf 页面转换为中间 png 文件的使用方式。当输出文件大小重要时使用此设置。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置一个值，指示垂直对齐方式。 |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

在最后一页打印事件上添加/移除订阅。

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

在最后一页打印事件上添加/移除订阅。

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

初始化新的 {@code PdfViewer} 对象。

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
初始化新的 {@code PdfViewer} 对象。

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
初始化 facade。

### bindPdf {#bindPdf-java.io.InputStream-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-}
初始化 facade。

### close {#close--}
```
public void close()
```

关闭当前的 Pdf 文件。

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

关闭当前的 Pdf 文件。

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

获取当前 pdf 文件的页面。

**Returns:**
返回 Pdf 页面图像的数组。

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

解码单个 Pdf 文件的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | Pdf 文件的页码，必须在 1 到 PageCount 之间。 |

**Returns:**
返回 Pdf 页面图像。

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
将页面解码为 BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

释放外观资源。此方法已过时，请改用 close()。

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

设置一个布尔值，指示文件是否以优化尺寸打印。

**Returns:**
布尔值：如果为 false，则在不进行页面缩放的情况下打印页面；如果为 true，则按比例缩放以适应可打印区域后打印页面。

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

获取一个布尔值，指示文件是否自动旋转打印。

**Returns:**
布尔值

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

获取 AutoRotateMode 值，指示旋转方向。

**Returns:**
AutoRotateMode 元素 @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

**Returns:**
PageCoordinateType 元素 @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

获取已打印的副本数

**Returns:**
int 值

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

获取默认页面设置。

**Returns:**
页面设置对象。

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

获取默认打印机设置。

**Returns:**
页面设置对象。

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

获取表单呈现模式。

**Returns:**
FormPresentationMode 元素 @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取指示水平对齐方式的值

**Returns:**
HorizontalAlignment 元素 @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

获取当前 Pdf 文件的页数。

**Returns:**
返回页面计数。

### getPassword {#getPassword--}
```
public String getPassword()
```

获取输入文档密码。

**Returns:**
字符串值

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 </p> <hr> 默认 false。

**Returns:**
布尔值

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> 获取 PdfViewer 以图像方式打印的模式。 </p>

**Returns:**
布尔值 <hr> 如果为 true，则始终以图像方式打印（生成要打印的图像）；如果为 false，则在所有功能受支持时直接打印到设备。如果文档包含不受支持的功能，系统可能会自动决定以图像方式打印。默认值为 false。

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

获取文档打印时在打印队列中的名称。默认值为文件名。

**Returns:**
字符串值

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

获取一个布尔值，指示打印时是否生成页码对话框。

**Returns:**
布尔值

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

获取打印作业的结果。如果成功则为 null；否则为异常对象。

**Returns:**
异常对象或 null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

获取渲染选项。

**Returns:**
RenderingOptions 对象

### getResolution {#getResolution--}
```
public int getResolution()
```

获取或设置查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。此属性在页面转图像的转换流程中更改图像分辨率：当 {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) 被设置为 {@code }，或调用 {@link #decodePage(int)} 或 {@link #decodeAllPages} 方法时。要为直接打印到打印机设置打印机分辨率，请使用 {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) 属性，位于 {@code PageSettings} 类中。

**Returns:**
int 值

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

获取指示缩放因子的浮点值。默认值为 1.0。

**Returns:**
浮点值。

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

获取在文件模式下打印时将 pdf 页面转换为中间 png 文件的使用情况。当输出文件大小很重要时使用它。

**Returns:**
布尔值。

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取指示垂直对齐方式的值

**Returns:**
VerticalAlignment 元素 @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

此方法已弃用，获取控制页面隐藏区域可见性的标志。

**Returns:**
布尔值

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> 打开一个 Pdf 文件流。但实际上并未解码该 Pdf 文件的页面。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream(\"d:\\\\test.pdf\"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> 打开一个 Pdf 文件，但实际上并未解码该 Pdf 文件的页面。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> 使用默认打印机打印 Pdf 文档。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 使用打印机设置打印 Pdf 文档。输出页面尺寸将适配文档的首页尺寸。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 使用设置打印 Pdf 文档。如果文档尺寸与页面尺寸不兼容，pdf.kit 将扩展以适配页面尺寸。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize(\"A4\", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> 打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@\"d:\\test.pdf\"))); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 打开并打印带有指定打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"), ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 打开并打印带有指定页面设置和打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize(\"A4\", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"),pgs,ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。

### printLargePdf {#printLargePdf-java.lang.String-}
<p> 打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf(\"d:\\test.pdf\"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 使用指定的打印机设置打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 使用指定的页面设置和打印机设置打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> 此方法已集成文件的打开和打印，您无需显式调用 OpenPdfFile()。

### save {#save-java.io.InputStream-}
将结果 PDF 文档保存到流中。

### save {#save-java.lang.String-}
将结果 PDF 文档保存到文件中。

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

设置一个布尔值，指示文件是否以优化尺寸打印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值：如果为 false，则在不进行页面缩放的情况下打印页面；如果为 true，则按比例缩放以适应可打印区域后打印页面。 |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

设置一个布尔值，指示文件是否使用自动旋转打印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

设置 AutoRotateMode 值，指示旋转方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | AutoRotateMode 元素 @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

设置表单呈现模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | FormPresentationMode 元素 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置一个值，指示水平对齐方式。

### setPassword {#setPassword-java.lang.String-}
设置输入文档的密码。

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 </p> <hr> 默认 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> 为 PdfViewer 设置以图像方式打印的模式。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 <hr> 如果为 true，则始终以图像方式打印（生成要打印的图像）；如果为 false，则在所有功能受支持时直接打印到设备。如果文档包含不受支持的功能，系统可能会自动决定以图像方式打印。默认值为 false。 |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
设置文档在打印队列中的名称。默认值为文件名。

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

设置一个布尔值，指示打印时是否生成页码对话框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
设置渲染选项。

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

设置查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。此属性会在页面转图像的转换流程中更改图像分辨率：当 {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) 被设置为 {@code }，或调用 {@link #decodePage(int)} 或 {@link #decodeAllPages} 方法时。若要为直接打印到打印机设置打印机分辨率，请使用 {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) 属性，位于 {@code PageSettings} 类中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

设置一个浮点值，指示缩放因子。默认值为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 浮点值。 |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

已弃用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

设置在文件模式下打印时将 pdf 页面转换为中间 png 文件的使用方式。当输出文件大小重要时使用此设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值。 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置一个值，指示垂直对齐方式。
