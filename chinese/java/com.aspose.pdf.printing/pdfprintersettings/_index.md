---
title: PdfPrinterSettings
second_title: 用于 Java API 参考的 Aspose.PDF
description: 指定有关如何打印文档的信息，包括打印它的打印机。
type: docs
weight: 14
url: /zh/java/com.aspose.pdf.printing/pdfprintersettings/
---
**遗产：**
java.lang.Object
```
public class PdfPrinterSettings
```

指定有关如何打印文档的信息，包括打印文档的打印机。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPrinterSettings()](#PdfPrinterSettings--) | 初始化 PrinterSettings 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [canDuplex()](#canDuplex--) | 获取一个值，该值指示打印机是否支持双面打印。 |
| [createMeasurementGraphics()](#createMeasurementGraphics--) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics(boolean value)](#createMeasurementGraphics-boolean-) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics(PrintPageSettings value)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | 获取 Graphics2D 对象 |
| [deepClone()](#deepClone--) | 获取克隆对象 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCopies()](#getCopies--) | 获取要打印的文档份数。 |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | 获取此打印机的默认页面设置。 |
| [getDuplex()](#getDuplex--) | 获取或设置双面打印的打印机设置。 |
| [getFromPage()](#getFromPage--) | 获取或设置要打印的第一页的页码。 |
| [getInstalledPrinters()](#getInstalledPrinters--) | 获取计算机上安装的所有打印机的名称。 |
| [getLandscapeAngle()](#getLandscapeAngle--) | 获取旋转纵向方向以产生横向方向的角度（以度为单位）。 |
| [getMaximumCopies()](#getMaximumCopies--) | 获取打印机允许用户一次打印的最大份数。 |
| [getMaximumPage()](#getMaximumPage--) | 获取或设置可在 PrintDialog 中选择的最大 FromPage 或 ToPage。 |
| [getMinimumPage()](#getMinimumPage--) | 获取或设置可在 PrintDialog 中选择的最小 FromPage 或 ToPage。 |
| [getPaperSizes()](#getPaperSizes--) | 获取此打印机支持的纸张尺寸。 |
| [getPaperSources()](#getPaperSources--) | 获取打印机上可用的纸张来源托盘。 |
| [getPrintFileName()](#getPrintFileName--) | 打印到文件时获取或设置文件名。 |
| [getPrintRange()](#getPrintRange--) | 获取或设置用户指定要打印的页码。 |
| [getPrinterName()](#getPrinterName--) | 获取或设置要使用的打印机的名称。 |
| [getPrinterResolutions()](#getPrinterResolutions--) | 获取此打印机支持的所有分辨率。 |
| [getPrinterSettings()](#getPrinterSettings--) | 返回 PrinterSettings 对象 |
| [getSelectedPages()](#getSelectedPages--) | 获取要打印的选定页数。 |
| [getToPage()](#getToPage--) | 获取或设置要打印的最后一页的页码。 |
| [hashCode()](#hashCode--) |  |
| [isCollate()](#isCollate--) | 获取或设置一个值，该值指示打印的文档是否经过整理。 |
| [isDefaultPrinter()](#isDefaultPrinter--) | 获取一个值，该值指示 PrinterName 属性是否指定默认打印机，除非用户显式设置 PrinterName。 |
| [isDirectPrintingSupported(ImageType format)](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | 获取一个值，该值指示打印机是否支持 DirectPrinting |
| [isDirectPrintingSupported(String filename)](#isDirectPrintingSupported-java.lang.String-) | 获取一个值，该值指示打印机是否支持 DirectPrinting |
| [isPlotter()](#isPlotter--) | 获取一个值，该值指示打印机是否为绘图仪。 |
| [isPrintToFile()](#isPrintToFile--) | 获取一个值，该值指示打印输出是否发送到文件而不是端口。 |
| [isSupportsColor()](#isSupportsColor--) | 获取一个值，该值指示此打印机是否支持彩色打印。 |
| [isValid()](#isValid--) | 获取一个值，该值指示 PrinterName 属性是否指定了有效的打印机。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCollate(boolean value)](#setCollate-boolean-) | 获取或设置一个值，该值指示打印的文档是否经过整理。 |
| [setCopies(short value)](#setCopies-short-) | 设置要打印的文档份数。 |
| [setDuplex(int value)](#setDuplex-int-) | 获取或设置双面打印的打印机设置。 |
| [setFromPage(int value)](#setFromPage-int-) | 获取或设置要打印的第一页的页码。 |
| [setMaximumPage(int value)](#setMaximumPage-int-) | 获取或设置可在 PrintDialog 中选择的最大 FromPage 或 ToPage。 |
| [setMinimumPage(int value)](#setMinimumPage-int-) | 获取或设置可在 PrintDialog 中选择的最小 FromPage 或 ToPage。 |
| [setPrintFileName(String value)](#setPrintFileName-java.lang.String-) | 设置要打印的文件名。 |
| [setPrintRange(int value)](#setPrintRange-int-) | 设置用户指定要打印的页码。 |
| [setPrintToFile(boolean value)](#setPrintToFile-boolean-) | 设置一个值，指示打印输出是否发送到文件而不是端口。 |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | 设置要使用的打印机的名称。 |
| [setSelectedPages(int[] pagesList)](#setSelectedPages-int---) | 设置要打印的选定页数。 |
| [setToPage(int value)](#setToPage-int-) | 设置要打印的最后一页的页码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPrinterSettings() {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```


初始化 PrinterSettings 类的新实例。

### canDuplex() {#canDuplex--}
```
public boolean canDuplex()
```


获取一个值，该值指示打印机是否支持双面打印。

**退货：**
boolean - 布尔值
### createMeasurementGraphics() {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```


获取 Graphics2D 对象

**退货：**
java.awt.Graphics2D - Graphics2D 对象
### createMeasurementGraphics(boolean value) {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```


获取 Graphics2D 对象

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

**退货：**
java.awt.Graphics2D - Graphics2D 对象
### createMeasurementGraphics(PrintPageSettings value) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings value)
```


获取 Graphics2D 对象

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | PrintPageSettings 值 |

**退货：**
java.awt.Graphics2D - Graphics2D 对象
### createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)
```


获取 Graphics2D 对象

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | PrintPageSettings 值 |
| honorOriginAtMargins | boolean | 布尔值 |

**退货：**
java.awt.Graphics2D - Graphics2D 对象
### deepClone() {#deepClone--}
```
public PdfPrinterSettings deepClone()
```


获取克隆对象

**退货：**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) PdfPrinterSettings 对象
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCopies() {#getCopies--}
```
public short getCopies()
```


获取要打印的文档份数。

**退货：**
短 - 份数
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


获取此打印机的默认页面设置。

**退货：**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) 默认页面设置
### getDuplex() {#getDuplex--}
```
public int getDuplex()
```


获取或设置双面打印的打印机设置。

**退货：**
int - 整数值
### getFromPage() {#getFromPage--}
```
public int getFromPage()
```


获取或设置要打印的第一页的页码。

**退货：**
int - 整数值
### getInstalledPrinters() {#getInstalledPrinters--}
```
public static ArrayList<String> getInstalledPrinters()
```


获取计算机上安装的所有打印机的名称。

**退货：**
java.util.ArrayList<java.lang.String> - ArrayList 对象
### getLandscapeAngle() {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```


获取旋转纵向方向以产生横向方向的角度（以度为单位）。

**退货：**
int - 整数值
### getMaximumCopies() {#getMaximumCopies--}
```
public int getMaximumCopies()
```


获取打印机允许用户一次打印的最大份数。

**退货：**
int - 整数值
### getMaximumPage() {#getMaximumPage--}
```
public int getMaximumPage()
```


获取或设置可在 PrintDialog 中选择的最大 FromPage 或 ToPage。

**退货：**
int - 整数值
### getMinimumPage() {#getMinimumPage--}
```
public int getMinimumPage()
```


获取或设置可在 PrintDialog 中选择的最小 FromPage 或 ToPage。

**退货：**
int - 整数值
### getPaperSizes() {#getPaperSizes--}
```
public ArrayList<PrintPaperSize> getPaperSizes()
```


获取此打印机支持的纸张尺寸。

**退货：**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSize> - ArrayList 对象
### getPaperSources() {#getPaperSources--}
```
public ArrayList<PrintPaperSource> getPaperSources()
```


获取打印机上可用的纸张来源托盘。

**退货：**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSource> - ArrayList 对象
### getPrintFileName() {#getPrintFileName--}
```
public String getPrintFileName()
```


打印到文件时获取或设置文件名。

**退货：**
java.lang.String - 字符串对象
### getPrintRange() {#getPrintRange--}
```
public int getPrintRange()
```


获取或设置用户指定要打印的页码。

**退货：**
int - 整数值
### getPrinterName() {#getPrinterName--}
```
public String getPrinterName()
```


获取或设置要使用的打印机的名称。

**退货：**
java.lang.String - 字符串对象
### getPrinterResolutions() {#getPrinterResolutions--}
```
public System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```


获取此打印机支持的所有分辨率。

**退货：**
com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection - PrinterResolutionCollection 对象
### getPrinterSettings() {#getPrinterSettings--}
```
public System.Drawing.Printing.PrinterSettings getPrinterSettings()
```


返回 PrinterSettings 对象

**退货：**
com.aspose.ms.System.Drawing.Printing.PrinterSettings - PrinterSettings 对象
### getSelectedPages() {#getSelectedPages--}
```
public int[] getSelectedPages()
```


获取要打印的选定页数。

**退货：**
整数[- pagesList 整型数组
### getToPage() {#getToPage--}
```
public int getToPage()
```


获取或设置要打印的最后一页的页码。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCollate() {#isCollate--}
```
public boolean isCollate()
```


获取或设置一个值，该值指示打印的文档是否经过整理。

**退货：**
boolean - 布尔值
### isDefaultPrinter() {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```


获取一个值，该值指示 PrinterName 属性是否指定默认打印机，除非用户显式设置 PrinterName。

**退货：**
boolean - 布尔值
### isDirectPrintingSupported(ImageType format) {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
```
public boolean isDirectPrintingSupported(ImageType format)
```


获取一个值，该值指示打印机是否支持 DirectPrinting

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图像类型对象 |

**退货：**
boolean - 布尔值
### isDirectPrintingSupported(String filename) {#isDirectPrintingSupported-java.lang.String-}
```
public boolean isDirectPrintingSupported(String filename)
```


获取一个值，该值指示打印机是否支持 DirectPrinting

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 字符串对象 |

**退货：**
boolean - 布尔值
### isPlotter() {#isPlotter--}
```
public boolean isPlotter()
```


获取一个值，该值指示打印机是否为绘图仪。

**退货：**
boolean - 布尔值
### isPrintToFile() {#isPrintToFile--}
```
public boolean isPrintToFile()
```


获取一个值，该值指示打印输出是否发送到文件而不是端口。

**退货：**
boolean - 布尔值
### isSupportsColor() {#isSupportsColor--}
```
public boolean isSupportsColor()
```


获取一个值，该值指示此打印机是否支持彩色打印。

**退货：**
boolean - 布尔值
### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个值，该值指示 PrinterName 属性是否指定了有效的打印机。

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




### setCollate(boolean value) {#setCollate-boolean-}
```
public void setCollate(boolean value)
```


获取或设置一个值，该值指示打印的文档是否经过整理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCopies(short value) {#setCopies-short-}
```
public void setCopies(short value)
```


设置要打印的文档份数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 复印数量 |

### setDuplex(int value) {#setDuplex-int-}
```
public void setDuplex(int value)
```


获取或设置双面打印的打印机设置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFromPage(int value) {#setFromPage-int-}
```
public void setFromPage(int value)
```


获取或设置要打印的第一页的页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setMaximumPage(int value) {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```


获取或设置可在 PrintDialog 中选择的最大 FromPage 或 ToPage。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setMinimumPage(int value) {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```


获取或设置可在 PrintDialog 中选择的最小 FromPage 或 ToPage。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPrintFileName(String value) {#setPrintFileName-java.lang.String-}
```
public void setPrintFileName(String value)
```


设置要打印的文件名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPrintRange(int value) {#setPrintRange-int-}
```
public void setPrintRange(int value)
```


设置用户指定要打印的页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PdfPrintRange 元素 |

### setPrintToFile(boolean value) {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```


设置一个值，指示打印输出是否发送到文件而不是端口。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public void setPrinterName(String value)
```


设置要使用的打印机的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setSelectedPages(int[] pagesList) {#setSelectedPages-int---}
```
public void setSelectedPages(int[] pagesList)
```


设置要打印的选定页数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pagesList | int[] | 整型数组 |

### setToPage(int value) {#setToPage-int-}
```
public void setToPage(int value)
```


设置要打印的最后一页的页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PdfPrintRange 元素 |

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
