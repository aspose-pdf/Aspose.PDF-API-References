---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Aspose.PDF for Java API 参考"
description: "指定纸张的尺寸。"
type: docs
weight: 100
url: /zh/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

指定纸张的尺寸。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | 初始化 PaperSize 类的新实例。 |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | 初始化 PaperSize 类的新实例。 |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | 初始化 PaperSize 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight](#getHeight--) | 获取或设置纸张的高度，单位为百分之一英寸。 |
| [getKind](#getKind--) | 获取纸张类型。 |
| [getPaperName](#getPaperName--) | 获取或设置纸张类型的名称。 |
| [getRawKind](#getRawKind--) | 获取或设置表示 PaperSize 值之一或自定义值的整数。 |
| [getWidth](#getWidth--) | 获取或设置纸张的宽度，单位为百分之一英寸。 |
| [setHeight](#setHeight-int-) | 获取或设置纸张的高度，单位为百分之一英寸。 |
| [setPaperName](#setPaperName-java.lang.String-) | 获取纸张类型的名称。 |
| [setWidth](#setWidth-int-) | 设置纸张的宽度，单位为百分之一英寸。 |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | 将 {@link PaperSize} 转换为 Windows 特定的 System.Drawing.Printing.PaperSize。 |
| [toString](#toString--) | 获取此实例的名称。 |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

初始化 PaperSize 类的新实例。

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
初始化 PaperSize 类的新实例。

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
初始化 PaperSize 类的新实例。

### getHeight {#getHeight--}
```
public int getHeight()
```

获取或设置纸张的高度，单位为百分之一英寸。

**Returns:**
int 值

### getKind {#getKind--}
```
public int getKind()
```

获取纸张类型。

**Returns:**
int 值 @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

获取或设置纸张类型的名称。

**Returns:**
字符串值

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

获取或设置表示 PaperSize 值之一或自定义值的整数。

**Returns:**
int 值

### getWidth {#getWidth--}
```
public int getWidth()
```

获取或设置纸张的宽度，单位为百分之一英寸。

**Returns:**
int 值

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

获取或设置纸张的高度，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPaperName {#setPaperName-java.lang.String-}
获取纸张类型的名称。

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

设置纸张的宽度，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
将 {@link PaperSize} 转换为 Windows 特定的 System.Drawing.Printing.PaperSize。

### toString {#toString--}
```
public String toString()
```

获取此实例的名称。

**Returns:**
字符串值
