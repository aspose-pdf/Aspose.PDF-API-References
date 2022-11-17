---
title: PrintPageSettings
second_title: 用于 Java API 参考的 Aspose.PDF
description: 指定应用于单个打印页面的设置。
type: docs
weight: 15
url: /zh/java/com.aspose.pdf.printing/printpagesettings/
---
**遗产：**
java.lang.Object
```
public class PrintPageSettings
```

指定应用于单个打印页面的设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintPageSettings()](#PrintPageSettings--) | 使用默认打印机初始化 PageSettings 类的新实例。 |
| [PrintPageSettings(PdfPrinterSettings value)](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 使用指定的打印机初始化 PageSettings 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取页面的大小，同时考虑由 Landscape 属性指定的页面方向。 |
| [getClass()](#getClass--) |  |
| [getHardMarginX()](#getHardMarginX--) | 获取页面左侧硬边距的 x 坐标（以百分之一英寸为单位）。 |
| [getHardMarginY()](#getHardMarginY--) | 获取页面顶部硬边距的 y 坐标，以百分之一英寸为单位。 |
| [getMargins()](#getMargins--) | 获取此页面的边距。 |
| [getPageSettings()](#getPageSettings--) | 获取页面设置 |
| [getPaperSize()](#getPaperSize--) | 获取页面的纸张大小。 |
| [getPaperSource()](#getPaperSource--) | 获取页面的纸张来源；例如，打印机的上托盘。 |
| [getPrintableArea()](#getPrintableArea--) | 获取打印机页面的可打印区域的边界。 |
| [getPrinterResolution()](#getPrinterResolution--) | 获取页面的打印机分辨率。 |
| [getPrinterSettings()](#getPrinterSettings--) | 获取与页面关联的打印机设置。 |
| [hashCode()](#hashCode--) |  |
| [isColor()](#isColor--) | 获取或设置一个值，该值指示页面是否应以彩色打印。 |
| [isLandscape()](#isLandscape--) | 获取或设置一个值，该值指示页面是横向打印还是纵向打印。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，该值指示页面是否应以彩色打印。 |
| [setLandscape(boolean value)](#setLandscape-boolean-) | 获取或设置一个值，该值指示页面是横向打印还是纵向打印。 |
| [setMargins(PrinterMargins value)](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | 设置此页面的页边距。 |
| [setPaperSize(PrintPaperSize value)](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | 设置页面的纸张大小。 |
| [setPaperSource(PrintPaperSource value)](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | 设置页面的纸张来源；例如，打印机的上托盘。 |
| [setPrinterResolution(PdfPrinterResolution value)](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | 设置页面的打印机分辨率。 |
| [setPrinterSettings(PdfPrinterSettings value)](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 设置与页面关联的打印机设置。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintPageSettings() {#PrintPageSettings--}
```
public PrintPageSettings()
```


使用默认打印机初始化 PageSettings 类的新实例。

### PrintPageSettings(PdfPrinterSettings value) {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public PrintPageSettings(PdfPrinterSettings value)
```


使用指定的打印机初始化 PageSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | PdfPrinterSettings 对象 |

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
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取页面的大小，同时考虑由 Landscape 属性指定的页面方向。

**退货：**
[Rectangle](../../java.awt/rectangle) - 矩形对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getHardMarginX() {#getHardMarginX--}
```
public float getHardMarginX()
```


获取页面左侧硬边距的 x 坐标（以百分之一英寸为单位）。

**退货：**
float - 浮点值
### getHardMarginY() {#getHardMarginY--}
```
public float getHardMarginY()
```


获取页面顶部硬边距的 y 坐标，以百分之一英寸为单位。

**退货：**
float - 浮点值
### getMargins() {#getMargins--}
```
public PrinterMargins getMargins()
```


获取此页面的边距。

**退货：**
[PrinterMargins](../../com.aspose.pdf.printing/printermargins) - PrinterMargins 对象
### getPageSettings() {#getPageSettings--}
```
public System.Drawing.Printing.PageSettings getPageSettings()
```


获取页面设置

**退货：**
com.aspose.ms.System.Drawing.Printing.PageSettings - PageSettings 对象
### getPaperSize() {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```


获取页面的纸张大小。

**退货：**
[PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) PrintPaperSize 对象
### getPaperSource() {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```


获取页面的纸张来源；例如，打印机的上托盘。

**退货：**
[PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) PrintPaperSource 对象
### getPrintableArea() {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```


获取打印机页面的可打印区域的边界。

**退货：**
[Rectangle](../../java.awt/rectangle) - 矩形对象
### getPrinterResolution() {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```


获取页面的打印机分辨率。

**退货：**
[PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) PdfPrinterResolution 对象
### getPrinterSettings() {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```


获取与页面关联的打印机设置。

**退货：**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) PdfPrinterSettings 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，该值指示页面是否应以彩色打印。

**退货：**
boolean - 布尔值
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


获取或设置一个值，该值指示页面是横向打印还是纵向打印。

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




### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，该值指示页面是否应以彩色打印。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLandscape(boolean value) {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```


获取或设置一个值，该值指示页面是横向打印还是纵向打印。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargins(PrinterMargins value) {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public void setMargins(PrinterMargins value)
```


设置此页面的页边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins 对象 |

### setPaperSize(PrintPaperSize value) {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
```
public void setPaperSize(PrintPaperSize value)
```


设置页面的纸张大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) | PrintPaperSize 对象 |

### setPaperSource(PrintPaperSource value) {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
```
public void setPaperSource(PrintPaperSource value)
```


设置页面的纸张来源；例如，打印机的上托盘。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) | PrintPaperSource 对象 |

### setPrinterResolution(PdfPrinterResolution value) {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
```
public void setPrinterResolution(PdfPrinterResolution value)
```


设置页面的打印机分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) | PdfPrinterResolution 对象 |

### setPrinterSettings(PdfPrinterSettings value) {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void setPrinterSettings(PdfPrinterSettings value)
```


设置与页面关联的打印机设置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | PdfPrinterSettings 对象 |

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
