---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本提取选项"
type: docs
weight: 5060
url: /zh/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

表示文本提取选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | 为指定的文本格式模式初始化 {@code TextExtractionOptions} 对象的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | 获取格式模式。 |
| [getScaleFactor](#getScaleFactor--) | 获取在纯模式下提取时用于缩放字体大小的因子。较小的值会导致提取的文本中出现更多空格。默认值为 1——不进行缩放；将值设为 0 则允许算法自动选择缩放比例。 |
| [setFormattingMode](#setFormattingMode-int-) | 设置格式模式。 |
| [setScaleFactor](#setScaleFactor-double-) | 设置在纯模式下提取时用于缩放字体大小的因子。较小的值会导致提取的文本中出现更多空格（范围 1 到 10）。默认值为 1——不进行缩放；将值设为 0 则允许算法自动选择缩放比例。 |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

为指定的文本格式模式初始化 {@code TextExtractionOptions} 对象的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattingMode |  | 文本格式模式值。 @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

获取格式模式。

**Returns:**
TextFormattingMode 值 @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

获取在纯模式下提取时用于缩放字体大小的因子。较小的值会导致提取的文本中出现更多空格。默认值为 1——不进行缩放；将值设为 0 则允许算法自动选择缩放比例。

**Returns:**
double 值

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

设置格式模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TextFormattingMode 值 @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

设置在纯模式下提取时用于缩放字体大小的因子。较小的值会导致提取的文本中出现更多空格（范围 1 到 10）。默认值为 1——不进行缩放；将值设为 0 则允许算法自动选择缩放比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
