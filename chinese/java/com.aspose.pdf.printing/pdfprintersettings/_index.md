---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Aspose.PDF for Java API 参考"
description: "指定有关文档打印方式的信息，包括执行打印的打印机。"
type: docs
weight: 50
url: /zh/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

指定有关文档打印方式的信息，包括执行打印的打印机。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | 初始化 PrinterSettings 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [canDuplex](#canDuplex--) | 获取一个值，指示打印机是否支持双面打印。 |
| [createMeasurementGraphics](#createMeasurementGraphics--) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | 获取 Graphics2D 对象 |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | 获取 Graphics2D 对象 |
| [deepClone](#deepClone--) | 获取克隆的对象 |
| [getCopies](#getCopies--) | 获取要打印的文档副本数。 |
| [getDefaultPageSettings](#getDefaultPageSettings--) | 获取此打印机的默认页面设置。 |
| [getDuplex](#getDuplex--) | 获取或设置双面打印的打印机设置。 |
| [getFromPage](#getFromPage--) | 获取或设置要打印的第一页的页码。 |
| [getInstalledPrinters](#getInstalledPrinters--) | 获取计算机上安装的所有打印机的名称。 |
| [getLandscapeAngle](#getLandscapeAngle--) | 获取将纵向方向旋转为横向方向的角度（单位：度）。 |
| [getMaximumCopies](#getMaximumCopies--) | 获取打印机一次允许用户打印的最大副本数。 |
| [getMaximumPage](#getMaximumPage--) | 获取或设置在 PrintDialog 中可以选择的最大 FromPage 或 ToPage。 |
| [getMinimumPage](#getMinimumPage--) | 获取或设置在 PrintDialog 中可以选择的最小 FromPage 或 ToPage。 |
| [getPaperSizes](#getPaperSizes--) | 获取此打印机支持的纸张尺寸。 |
| [getPaperSources](#getPaperSources--) | 获取打印机上可用的纸张来源托盘。 |
| [getPrinterName](#getPrinterName--) | 获取或设置要使用的打印机名称。 |
| [getPrinterResolutions](#getPrinterResolutions--) | 获取此打印机支持的所有分辨率。 |
| [getPrinterSettings](#getPrinterSettings--) | 返回 PrinterSettings 对象 |
| [getPrintFileName](#getPrintFileName--) | 获取或设置打印到文件时的文件名。 |
| [getPrintRange](#getPrintRange--) | 获取或设置用户指定要打印的页码。 |
| [getSelectedPages](#getSelectedPages--) | 获取要打印的已选择页数。 |
| [getToPage](#getToPage--) | 获取或设置要打印的最后一页页码。 |
| [isCollate](#isCollate--) | 获取或设置一个值，指示打印的文档是否已排序。 |
| [isDefaultPrinter](#isDefaultPrinter--) | 获取一个值，指示 PrinterName 属性是否指定默认打印机，除非用户显式设置了 PrinterName。 |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | 获取一个值，指示打印机是否支持直接打印。 |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | 获取一个值，指示打印机是否支持直接打印。 |
| [isPlotter](#isPlotter--) | 获取一个值，指示打印机是否为绘图仪。 |
| [isPrintToFile](#isPrintToFile--) | 获取一个值，指示打印输出是发送到文件而不是端口。 |
| [isSupportsColor](#isSupportsColor--) | 获取一个值，指示此打印机是否支持彩色打印。 |
| [isValid](#isValid--) | 获取一个值，指示 PrinterName 属性是否指定了有效的打印机。 |
| [setCollate](#setCollate-boolean-) | 获取或设置一个值，指示打印的文档是否已排序。 |
| [setCopies](#setCopies-short-) | 设置要打印的文档副本数。 |
| [setDuplex](#setDuplex-int-) | 获取或设置双面打印的打印机设置。 |
| [setFromPage](#setFromPage-int-) | 获取或设置要打印的第一页的页码。 |
| [setMaximumPage](#setMaximumPage-int-) | 获取或设置在 PrintDialog 中可以选择的最大 FromPage 或 ToPage。 |
| [setMinimumPage](#setMinimumPage-int-) | 获取或设置在 PrintDialog 中可以选择的最小 FromPage 或 ToPage。 |
| [setPrinterName](#setPrinterName-java.lang.String-) | 设置要使用的打印机名称。 |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | 设置要打印的文件名。 |
| [setPrintRange](#setPrintRange-int-) | 设置用户指定要打印的页码。 |
| [setPrintToFile](#setPrintToFile-boolean-) | 设置一个值，指示打印输出是发送到文件而不是端口。 |
| [setSelectedPages](#setSelectedPages-int:A-) | 设置要打印的已选择页数。 |
| [setToPage](#setToPage-int-) | 设置要打印的最后一页页码。 |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

初始化 PrinterSettings 类的新实例。

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

获取一个值，指示打印机是否支持双面打印。

**Returns:**
布尔值

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

获取 Graphics2D 对象

**Returns:**
Graphics2D 对象

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

获取 Graphics2D 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

**Returns:**
Graphics2D 对象

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
获取 Graphics2D 对象

**Returns:**
Graphics2D 对象

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
获取 Graphics2D 对象

**Returns:**
Graphics2D 对象

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

获取克隆的对象

**Returns:**
PdfPrinterSettings 对象

### getCopies {#getCopies--}
```
public short getCopies()
```

获取要打印的文档副本数。

**Returns:**
副本数量

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

获取此打印机的默认页面设置。

**Returns:**
默认页面设置

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

获取或设置双面打印的打印机设置。

**Returns:**
int 值 @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

获取或设置要打印的第一页的页码。

**Returns:**
int 值

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

获取计算机上安装的所有打印机的名称。

**Returns:**
{@code ArrayList<String>} 对象

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

获取将纵向方向旋转为横向方向的角度（单位：度）。

**Returns:**
int 值

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

获取打印机一次允许用户打印的最大副本数。

**Returns:**
int 值

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

获取或设置在 PrintDialog 中可以选择的最大 FromPage 或 ToPage。

**Returns:**
int 值

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

获取或设置在 PrintDialog 中可以选择的最小 FromPage 或 ToPage。

**Returns:**
int 值

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

获取此打印机支持的纸张尺寸。

**Returns:**
{@code ArrayList<PrintPaperSize> } 对象

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

获取打印机上可用的纸张来源托盘。

**Returns:**
{@code ArrayList<PrintPaperSource> } 对象

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

获取或设置要使用的打印机名称。

**Returns:**
字符串对象

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

获取此打印机支持的所有分辨率。

**Returns:**
PrinterResolutionCollection 对象

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

返回 PrinterSettings 对象

**Returns:**
PrinterSettings 对象

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

获取或设置打印到文件时的文件名。

**Returns:**
字符串对象

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

获取或设置用户指定要打印的页码。

**Returns:**
int 值 @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

获取要打印的已选择页数。

**Returns:**
pagesList int 数组 @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

获取或设置要打印的最后一页页码。

**Returns:**
int 值

### isCollate {#isCollate--}
```
public boolean isCollate()
```

获取或设置一个值，指示打印的文档是否已排序。

**Returns:**
布尔值

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

获取一个值，指示 PrinterName 属性是否指定默认打印机，除非用户显式设置了 PrinterName。

**Returns:**
布尔值

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
获取一个值，指示打印机是否支持直接打印。

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
获取一个值，指示打印机是否支持直接打印。

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

获取一个值，指示打印机是否为绘图仪。

**Returns:**
布尔值

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

获取一个值，指示打印输出是发送到文件而不是端口。

**Returns:**
布尔值

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

获取一个值，指示此打印机是否支持彩色打印。

**Returns:**
布尔值

### isValid {#isValid--}
```
public boolean isValid()
```

获取一个值，指示 PrinterName 属性是否指定了有效的打印机。

**Returns:**
布尔值

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

获取或设置一个值，指示打印的文档是否已排序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

设置要打印的文档副本数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 副本数量 |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

获取或设置双面打印的打印机设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

获取或设置要打印的第一页的页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

获取或设置在 PrintDialog 中可以选择的最大 FromPage 或 ToPage。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

获取或设置在 PrintDialog 中可以选择的最小 FromPage 或 ToPage。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPrinterName {#setPrinterName-java.lang.String-}
设置要使用的打印机名称。

### setPrintFileName {#setPrintFileName-java.lang.String-}
设置要打印的文件名。

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

设置用户指定要打印的页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PdfPrintRange 元素 @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

设置一个值，指示打印输出是发送到文件而不是端口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

设置要打印的已选择页数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pagesList |  | int 数组 @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

设置要打印的最后一页页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PdfPrintRange 元素 @see PdfPrintRange |
