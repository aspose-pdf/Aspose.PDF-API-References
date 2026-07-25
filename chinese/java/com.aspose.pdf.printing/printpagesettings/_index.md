---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Aspose.PDF for Java API 参考"
description: "指定适用于单个打印页面的设置。"
type: docs
weight: 90
url: /zh/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

指定适用于单个打印页面的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | 使用默认打印机初始化 PageSettings 类的新实例。 |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 使用默认打印机初始化 PageSettings 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds](#getBounds--) | 获取页面的大小，考虑由 Landscape 属性指定的页面方向。 |
| [getHardMarginX](#getHardMarginX--) | 获取页面左侧硬边距的 x 坐标（以百分之一英寸为单位）。 |
| [getHardMarginY](#getHardMarginY--) | 获取页面顶部硬边距的 y 坐标（以百分之一英寸为单位）。 |
| [getMargins](#getMargins--) | 获取此页面的边距。 |
| [getPageSettings](#getPageSettings--) | 获取页面设置 |
| [getPaperSize](#getPaperSize--) | 获取页面的纸张尺寸。 |
| [getPaperSource](#getPaperSource--) | 获取页面的纸张来源；例如，打印机的上托盘。 |
| [getPrintableArea](#getPrintableArea--) | 获取页面可打印区域的边界（针对打印机）。 |
| [getPrinterResolution](#getPrinterResolution--) | 获取页面的打印机分辨率。 |
| [getPrinterSettings](#getPrinterSettings--) | 获取与页面关联的打印机设置。 |
| [isColor](#isColor--) | 获取或设置指示页面是否应以彩色打印的值。 |
| [isLandscape](#isLandscape--) | 获取或设置指示页面是以横向还是纵向打印的值。 |
| [setColor](#setColor-boolean-) | 获取或设置指示页面是否应以彩色打印的值。 |
| [setLandscape](#setLandscape-boolean-) | 获取或设置指示页面是以横向还是纵向打印的值。 |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | 设置此页面的边距。 |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | 设置页面的纸张尺寸。 |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | 设置页面的纸张来源；例如，打印机的上托盘。 |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | 设置页面的打印机分辨率。 |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | 设置与页面关联的打印机设置。 |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

使用默认打印机初始化 PageSettings 类的新实例。

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
使用默认打印机初始化 PageSettings 类的新实例。

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

获取页面的大小，考虑由 Landscape 属性指定的页面方向。

**Returns:**
Rectangle 对象

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

获取页面左侧硬边距的 x 坐标（以百分之一英寸为单位）。

**Returns:**
float 值

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

获取页面顶部硬边距的 y 坐标（以百分之一英寸为单位）。

**Returns:**
float 值

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

获取此页面的边距。

**Returns:**
PrinterMargins 对象

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

获取页面设置

**Returns:**
PageSettings 对象

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

获取页面的纸张尺寸。

**Returns:**
PrintPaperSize 对象

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

获取页面的纸张来源；例如，打印机的上托盘。

**Returns:**
PrintPaperSource 对象

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

获取页面可打印区域的边界（针对打印机）。

**Returns:**
Rectangle 对象

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

获取页面的打印机分辨率。

**Returns:**
PdfPrinterResolution 对象

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

获取与页面关联的打印机设置。

**Returns:**
PdfPrinterSettings 对象

### isColor {#isColor--}
```
public boolean isColor()
```

获取或设置指示页面是否应以彩色打印的值。

**Returns:**
布尔值

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

获取或设置指示页面是以横向还是纵向打印的值。

**Returns:**
布尔值

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

获取或设置指示页面是否应以彩色打印的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

获取或设置指示页面是以横向还是纵向打印的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
设置此页面的边距。

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
设置页面的纸张尺寸。

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
设置页面的纸张来源；例如，打印机的上托盘。

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
设置页面的打印机分辨率。

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
设置与页面关联的打印机设置。
