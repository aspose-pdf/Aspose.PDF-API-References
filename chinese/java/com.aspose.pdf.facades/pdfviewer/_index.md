---
title: PdfViewer
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示查看或打印 pdf 的类。
type: docs
weight: 53
url: /zh/java/com.aspose.pdf.facades/pdfviewer/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget

**所有已实现的接口：**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public final class PdfViewer extends IVentureLicenseTarget implements IFacade
```

表示查看或打印 pdf 的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfViewer()](#PdfViewer--) | 初始化新的 PdfViewer 对象。 |
| [PdfViewer(IDocument document)](#PdfViewer-com.aspose.pdf.IDocument-) | 初始化新的 PdfViewer 对象。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [EndPrint](#EndPrint) | 添加/删除对最后一页打印事件的订阅。 |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | 添加/删除对最后一页打印事件的订阅。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭当前的 Pdf 文件。 |
| [closePdfFile()](#closePdfFile--) | 关闭当前的 Pdf 文件。 |
| [decodeAllPages()](#decodeAllPages--) | 获取当前 pdf 文件的页面。 |
| [decodePage(int pageNumber)](#decodePage-int-) | 解码一个 Pdf 文件的一页。 |
| [decodePageToImage(int pageNumber, ImageType imageFormat)](#decodePageToImage-int-com.aspose.pdf.ImageType-) | 将页面解码为 BufferedImage |
| [dispose()](#dispose--) | 处理门面资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoResize()](#getAutoResize--) | 设置一个 bool 值，指示文件是否以优化大小打印。 |
| [getAutoRotate()](#getAutoRotate--) | 获取一个 bool 值，指示文件是否自动旋转打印 |
| [getAutoRotateMode()](#getAutoRotateMode--) | 获取指示旋转方向的 AutoRotateMode 值 |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | 获取页面坐标类型（媒体/裁剪框）。 |
| [getCopiesPrinted()](#getCopiesPrinted--) | 打印副本 |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | 获取默认页面设置。 |
| [getDefaultPrinterSettings()](#getDefaultPrinterSettings--) | 获取默认打印机设置。 |
| [getFormPresentationMode()](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取指示水平对齐的值 |
| [getPageCount()](#getPageCount--) | 获取当前 Pdf 文件的页数。 |
| [getPassword()](#getPassword--) | 获取输入文档密码。 |
| [getPrintAsGrayscale()](#getPrintAsGrayscale--) | 获取或设置一个 bool 值，该值指示页面是否以灰度打印。 |
| [getPrintAsImage()](#getPrintAsImage--) | 获取 PdfViewer 打印为图像的模式。 |
| [getPrintPageDialog()](#getPrintPageDialog--) | 获取一个布尔值，表示打印时是否产生页码对话框。 |
| [getPrintStatus()](#getPrintStatus--) | 获取打印作业的结果。 |
| [getPrinterJobName()](#getPrinterJobName--) | 打印文档时获取打印机队列中文档的名称。 |
| [getRenderingOptions()](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution()](#getResolution--) | 获取或设置查看和打印期间的分辨率。 |
| [getScaleFactor()](#getScaleFactor--) | 获取表示比例因子的浮点值。 |
| [getUseIntermidiateImage()](#getUseIntermidiateImage--) | 获取在文件模式下打印时将pdf页面转换为中间png文件的使用。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取表示垂直对齐的值 |
| [hashCode()](#hashCode--) |  |
| [isShowHiddenAreas()](#isShowHiddenAreas--) | 此方法已弃用 获取控制页面上隐藏区域可见性的标志。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openPdfFile(InputStream inputStream)](#openPdfFile-java.io.InputStream-) | 打开一个 Pdf 文件流。 |
| [openPdfFile(String filePath)](#openPdfFile-java.lang.String-) | 打开一个 Pdf 文件，但实际上并不解码 Pdf 文件的页面。 |
| [printDocument()](#printDocument--) | 使用默认打印机打印 Pdf 文档。 |
| [printDocumentWithSettings(PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 使用打印机设置打印 Pdf 文档。 |
| [printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 打印带有设置的 Pdf 文档。 |
| [printLargePdf(InputStream inputStream)](#printLargePdf-java.io.InputStream-) | 打开并打印大型 Pdf 流。 |
| [printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | 打开并打印具有指定打印机设置的大型 Pdf 流。 |
| [printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 打开并打印具有指定页面设置和打印机设置的大型 Pdf 流。 |
| [printLargePdf(String filePath)](#printLargePdf-java.lang.String-) | 打开并打印大型 Pdf 文件。 |
| [printLargePdf(String filePath, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | 打开并打印具有指定打印机设置的大型 Pdf 文件。 |
| [printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 打开并打印具有指定页面设置和打印机设置的大型 Pdf 文件。 |
| [save(InputStream destStream)](#save-java.io.InputStream-) | 将结果 PDF 文档保存到流中。 |
| [save(String destFile)](#save-java.lang.String-) | 将结果 PDF 文档保存到文件。 |
| [setAutoResize(boolean value)](#setAutoResize-boolean-) | 设置一个 bool 值，指示文件是否以优化大小打印。 |
| [setAutoRotate(boolean value)](#setAutoRotate-boolean-) | 设置一个 bool 值，指示文件是否自动旋转打印 |
| [setAutoRotateMode(int value)](#setAutoRotateMode-int-) | 设置指示旋转方向的 AutoRotateMode 值 |
| [setCoordinateType(int value)](#setCoordinateType-int-) | 设置页面坐标类型（媒体/裁剪框）。 |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置一个指示水平对齐的值 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置输入文档密码。 |
| [setPrintAsGrayscale(boolean value)](#setPrintAsGrayscale-boolean-) | 获取或设置一个 bool 值，该值指示页面是否以灰度打印。 |
| [setPrintAsImage(boolean value)](#setPrintAsImage-boolean-) | 设置 PdfViewer 打印为图像的模式。 |
| [setPrintPageDialog(boolean value)](#setPrintPageDialog-boolean-) | 设置一个布尔值，指示打印时是否产生页码对话框。 |
| [setPrinterJobName(String value)](#setPrinterJobName-java.lang.String-) | 打印文档时设置打印机队列中文档的名称。 |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setResolution(int value)](#setResolution-int-) | 在查看和打印期间设置分辨率。 |
| [setScaleFactor(float value)](#setScaleFactor-float-) | 设置表示比例因子的浮点值。 |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [setUseIntermidiateImage(boolean value)](#setUseIntermidiateImage-boolean-) | 设置在文件模式下打印时将pdf页面转换为中间png文件的使用。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置一个表示垂直对齐的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfViewer() {#PdfViewer--}
```
public PdfViewer()
```


初始化新的 PdfViewer 对象。

### PdfViewer(IDocument document) {#PdfViewer-com.aspose.pdf.IDocument-}
```
public PdfViewer(IDocument document)
```


初始化新的 PdfViewer 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### EndPrint {#EndPrint}
```
public final PdfEvent<System.Drawing.Printing.PrintEventHandler> EndPrint
```


添加/删除对最后一页打印事件的订阅。

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent<PdfQueryPageSettingsEventHandler> PdfQueryPageSettings
```


添加/删除对最后一页打印事件的订阅。

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### close() {#close--}
```
public void close()
```


关闭当前的 Pdf 文件。

### closePdfFile() {#closePdfFile--}
```
public void closePdfFile()
```


关闭当前的 Pdf 文件。

### decodeAllPages() {#decodeAllPages--}
```
public BufferedImage[] decodeAllPages()
```


获取当前 pdf 文件的页面。

**退货：**
java.awt.image.BufferedImage[] - 返回 Pdf 页面图像数组。
### decodePage(int pageNumber) {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```


解码一个 Pdf 文件的一页。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 一个 Pdf 文件的页码，必须介于 1 和 PageCount 之间。 |

**退货：**
java.awt.image.BufferedImage - 返回 Pdf 页面图像。
### decodePageToImage(int pageNumber, ImageType imageFormat) {#decodePageToImage-int-com.aspose.pdf.ImageType-}
```
public BufferedImage decodePageToImage(int pageNumber, ImageType imageFormat)
```


将页面解码为 BufferedImage

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 整数值 |
| imageFormat | [ImageType](../../com.aspose.pdf/imagetype) | 图像类型对象 |

**退货：**
java.awt.image.BufferedImage - BufferedImage 值
### dispose() {#dispose--}
```
public void dispose()
```


处理门面资源。

此方法已过时，请改用 close() 。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getAutoResize() {#getAutoResize--}
```
public boolean getAutoResize()
```


设置一个 bool 值，指示文件是否以优化大小打印。

**退货：**
boolean - 布尔值：如果为 false，则不进行页面缩放打印页面。如果 true 打印页面缩放以适合可打印区域。
### getAutoRotate() {#getAutoRotate--}
```
public boolean getAutoRotate()
```


获取一个 bool 值，指示文件是否自动旋转打印

**退货：**
boolean - 布尔值
### getAutoRotateMode() {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```


获取指示旋转方向的 AutoRotateMode 值

**退货：**
int - AutoRotateMode 元素
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


获取页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**退货：**
int - PageCoordinateType 元素
### getCopiesPrinted() {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```


打印副本

**退货：**
int - 整数值
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


获取默认页面设置。

**退货：**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) 页面设置对象。
### getDefaultPrinterSettings() {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```


获取默认打印机设置。

**退货：**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) 页面设置对象。
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


获取表单呈现模式。

**退货：**
int - FormPresentationMode 元素
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取指示水平对齐的值

**退货：**
int - HorizontalAlignment 元素
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


获取当前 Pdf 文件的页数。

**退货：**
int - 返回页数。
### getPassword() {#getPassword--}
```
public String getPassword()
```


获取输入文档密码。

**退货：**
java.lang.String - 字符串值
### getPrintAsGrayscale() {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```


获取或设置一个 bool 值，该值指示页面是否以灰度打印。默认情况下是假的。

--------------------

默认 false 为假。

**退货：**
boolean - 布尔值
### getPrintAsImage() {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```


获取 PdfViewer 打印为图像的模式。

**退货：**
boolean - 布尔值

--------------------

如果 true 始终打印为图像（生成打印的图像），如果支持所有功能，则直接打印到设备。如果文档包含不受支持的功能，系统可能会自动决定打印为图像。默认值为 false。
### getPrintPageDialog() {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```


获取一个布尔值，表示打印时是否产生页码对话框。

**退货：**
boolean - 布尔值
### getPrintStatus() {#getPrintStatus--}
```
public Object getPrintStatus()
```


获取打印作业的结果。如果成功则为空；否则，异常对象。

**退货：**
java.lang.Object - 异常对象或 null
### getPrinterJobName() {#getPrinterJobName--}
```
public String getPrinterJobName()
```


打印文档时获取打印机队列中文档的名称。默认值为文件名。

**退货：**
java.lang.String - 字符串值
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


获取渲染选项。

**退货：**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) 渲染选项对象
### getResolution() {#getResolution--}
```
public int getResolution()
```


获取或设置查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。

**退货：**
int - 整数值
### getScaleFactor() {#getScaleFactor--}
```
public float getScaleFactor()
```


获取表示比例因子的浮点值。默认值为 1.0。

**退货：**
float - 浮点值。
### getUseIntermidiateImage() {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```


获取在文件模式下打印时将pdf页面转换为中间png文件的使用。当输出文件的大小很重要时使用它。

**退货：**
boolean - 布尔值。
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取表示垂直对齐的值

**退货：**
int - VerticalAlignment 元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isShowHiddenAreas() {#isShowHiddenAreas--}
```
public boolean isShowHiddenAreas()
```


此方法已弃用 获取控制页面上隐藏区域可见性的标志。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### openPdfFile(InputStream inputStream) {#openPdfFile-java.io.InputStream-}
```
public void openPdfFile(InputStream inputStream)
```


打开一个 Pdf 文件流。但实际上并没有解码 Pdf 文件的页面。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile(new FileInputStream("d:\\test.pdf")));
 viewer.closePdfFile();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要打开的 pdf 流。 |

### openPdfFile(String filePath) {#openPdfFile-java.lang.String-}
```
public void openPdfFile(String filePath)
```


打开一个 Pdf 文件，但实际上并不解码 Pdf 文件的页面。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.closePdfFile();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | Pdf 文件的路径。 |

### printDocument() {#printDocument--}
```
public void printDocument()
```


使用默认打印机打印 Pdf 文档。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);   //do not produce the page number dialog when printing
 viewer.printDocument(ps);
 viewer.closePdfFile();
```

### printDocumentWithSettings(PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PdfPrinterSettings printerSettings)
```


使用打印机设置打印 Pdf 文档。输出页面大小将适合文档首页大小。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);   //do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName());
 viewer.printDocumentWithSettings(ps);
 viewer.closePdfFile();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印文档的打印机设置。 |

### printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


打印带有设置的 Pdf 文档。如果文档大小与页面大小不兼容，pdf.kit 将扩展它以适应页面大小。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printDocumentWithSettings(pgs, ps);
 viewer.closePdfFile();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | 打印文档的页面设置。 |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印文档的打印机设置。

--------------------

printerSettings 对象用于打印文档。 pageSettings.PrinterSettings 对象被忽略。|

### printLargePdf(InputStream inputStream) {#printLargePdf-java.io.InputStream-}
```
public void printLargePdf(InputStream inputStream)
```


打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);        //print the file with adjusted size
 viewer.setAutoRotate ( true);        //print the file with adjusted rotation
 viewer.printPageDialog=false;//do not produce the page number dialog when printing
 viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
 viewer.closePdfFile();
```

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要打开和打印的 pdf 流.. |

### printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)
```


打开并打印具有指定打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false); // do not produce the page number dialog when
 				  // printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps);
 viewer.closePdfFile();
```

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要打开和打印的 pdf 流.. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印机设置。 |

### printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


打开并打印具有指定页面设置和打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //print the file with adjusted size
 viewer.setAutoRotate ( true);       //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps);
 viewer.closePdfFile();
```

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要打开和打印的 pdf 流。 |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | 页面设置。 |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印机设置。 |

### printLargePdf(String filePath) {#printLargePdf-java.lang.String-}
```
public void printLargePdf(String filePath)
```


打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false);// do not produce the page number dialog when
 									// printing
 viewer.setPrintLargePdf("d:\test.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | Pdf 文件的路径。

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。|

### printLargePdf(String filePath, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PdfPrinterSettings printerSettings)
```


打开并打印具有指定打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //print the file with adjusted size
 viewer.setAutoRotate ( true);       //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf("d:\\test.pdf",ps);
 viewer.closePdfFile();
```

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | Pdf 文件的路径。 |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印机设置。 |

### printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


打开并打印具有指定页面设置和打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或者其大小超过 3 MB，建议使用此方法以获得更好的性能。

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false); // do not produce the page number dialog when
 				  // printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize(new PaperSize("A4", 827, 1169));
 pgs.setMargins(new Margins(0, 0, 0, 0));
 viewer.printLargePdf("d:\\test.pdf", pgs, ps);
 viewer.closePdfFile();
```

--------------------

该方法集成了文件的打开和打印，无需显式调用OpenPdfFile()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | Pdf 文件的路径。 |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | 页面设置。 |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | 打印机设置。 |

### save(InputStream destStream) {#save-java.io.InputStream-}
```
public void save(InputStream destStream)
```


将结果 PDF 文档保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.InputStream | 输出 PDF 文档的流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将结果 PDF 文档保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 输出PDF文档的路径。 |

### setAutoResize(boolean value) {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```


设置一个 bool 值，指示文件是否以优化大小打印。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值：如果为 false，则不进行页面缩放打印页面。如果 true 打印页面缩放以适合可打印区域。 |

### setAutoRotate(boolean value) {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```


设置一个 bool 值，指示文件是否自动旋转打印

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAutoRotateMode(int value) {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```


设置指示旋转方向的 AutoRotateMode 值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | AutoRotateMode 元素 |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PageCoordinateType 元素 |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


设置表单呈现模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | FormPresentationMode 元素 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置一个指示水平对齐的值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 元素 |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


设置输入文档密码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPrintAsGrayscale(boolean value) {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```


获取或设置一个 bool 值，该值指示页面是否以灰度打印。默认情况下是假的。

--------------------

默认 false 为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPrintAsImage(boolean value) {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```


设置 PdfViewer 打印为图像的模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值

--------------------

如果 true 始终打印为图像（生成打印的图像），如果支持所有功能，则直接打印到设备。如果文档包含不受支持的功能，系统可能会自动决定打印为图像。默认值为 false。|

### setPrintPageDialog(boolean value) {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```


设置一个布尔值，指示打印时是否产生页码对话框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPrinterJobName(String value) {#setPrinterJobName-java.lang.String-}
```
public void setPrinterJobName(String value)
```


打印文档时设置打印机队列中文档的名称。默认值为文件名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


设置渲染选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | RenderingOptions 值 |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


在查看和打印期间设置分辨率。分辨率越高，速度越慢。默认值为 150。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setScaleFactor(float value) {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```


设置表示比例因子的浮点值。默认值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值。 |

### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setUseIntermidiateImage(boolean value) {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```


设置在文件模式下打印时将pdf页面转换为中间png文件的使用。当输出文件的大小很重要时使用它。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值。 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置一个表示垂直对齐的值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
