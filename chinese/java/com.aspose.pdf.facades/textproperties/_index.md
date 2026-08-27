---
title: "TextProperties"
linktitle: "TextProperties"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本属性，例如：文本大小、颜色、样式等。"
type: docs
weight: 740
url: /zh/java/com.aspose.pdf.facades/textproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.TextProperties

```
public final class TextProperties extends Object
```

表示文本属性，例如：文本大小、颜色、样式等。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextProperties](#TextProperties-double-) | 为指定的文本大小创建 {@code TextProperties} 对象 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor](#getColor--) | 获取文本颜色。 |
| [getTextSize](#getTextSize--) | 获取文本大小。 |
| [isColorSpecified](#isColorSpecified--) | 获取一个值，指示是否已指定 {@code Color} 属性。 |
| [isTextSizeSpecified](#isTextSizeSpecified--) | 获取一个值，指示是否已指定 {@code TextSize} 属性。 |
| [setColor](#setColor-java.awt.Color-) | 设置文本颜色。 |
| [setTextSize](#setTextSize-double-) | 设置文本大小。 |

### TextProperties {#TextProperties-double-}
```
public TextProperties(double textSize)
```

为指定的文本大小创建 {@code TextProperties} 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textSize |  | 文本大小值。 |

### getColor {#getColor--}
```
public Color getColor()
```

获取文本颜色。

**Returns:**
Color 对象

### getTextSize {#getTextSize--}
```
public double getTextSize()
```

获取文本大小。

**Returns:**
double 值

### isColorSpecified {#isColorSpecified--}
```
public boolean isColorSpecified()
```

获取一个值，指示是否已指定 {@code Color} 属性。

**Returns:**
布尔值

### isTextSizeSpecified {#isTextSizeSpecified--}
```
public boolean isTextSizeSpecified()
```

获取一个值，指示是否已指定 {@code TextSize} 属性。

**Returns:**
布尔值

### setColor {#setColor-java.awt.Color-}
设置文本颜色。

### setTextSize {#setTextSize-double-}
```
public void setTextSize(double value)
```

设置文本大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
