---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示条形码字段的类。"
type: docs
weight: 250
url: /zh/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

表示条形码字段的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 初始化 {@code BarcodeField} 类的新实例。 |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 初始化 {@code BarcodeField} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaption](#getCaption--) | 获取条形码对象的标题。 |
| [getECC](#getECC--) | 获取表示错误纠正系数的整数值。对于 PDF417，应在 0 到 8 之间。对于 QRCode，应在 0 到 3 之间（0 对应 'L'，1 对应 'M'，2 对应 'Q'，3 对应 'H'）。 |
| [getResolution](#getResolution--) | 获取条码对象渲染时的分辨率，单位为每英寸点数（dpi）。 |
| [getSymbology](#getSymbology--) | 指定在此注释上使用的条码或字形技术，详情请参阅 {@code Symbology}。 |
| [getXSymHeight](#getXSymHeight--) | 获取两个条码模块之间的垂直距离，单位为像素。比例 XSymHeight/XSymWidth 必须为整数。对于 PDF417，可接受的比例范围为 1 到 4。对于 QRCode 和 DataMatrix，该比例始终为 1。 |
| [getXSymWidth](#getXSymWidth--) | 获取两个条码模块之间的水平距离，单位为像素。 |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
初始化 {@code BarcodeField} 类的新实例。

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
初始化 {@code BarcodeField} 类的新实例。

### getCaption {#getCaption--}
```
public String getCaption()
```

获取条形码对象的标题。

**Returns:**
字符串值

### getECC {#getECC--}
```
public int getECC()
```

获取表示错误纠正系数的整数值。对于 PDF417，应在 0 到 8 之间。对于 QRCode，应在 0 到 3 之间（0 对应 'L'，1 对应 'M'，2 对应 'Q'，3 对应 'H'）。

**Returns:**
int 值

### getResolution {#getResolution--}
```
public int getResolution()
```

获取条码对象渲染时的分辨率，单位为每英寸点数（dpi）。

**Returns:**
int 值

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

指定在此注释上使用的条码或字形技术，详情请参阅 {@code Symbology}。

**Returns:**
Symbology 元素 @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

获取两个条码模块之间的垂直距离，单位为像素。比例 XSymHeight/XSymWidth 必须为整数。对于 PDF417，可接受的比例范围为 1 到 4。对于 QRCode 和 DataMatrix，该比例始终为 1。

**Returns:**
int 值

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

获取两个条码模块之间的水平距离，单位为像素。

**Returns:**
int 值
