---
title: "DefaultAppearance"
linktitle: "DefaultAppearance"
second_title: "Aspose.PDF for Java API 参考"
description: "描述字段的默认外观（字体、文字大小和颜色）。"
type: docs
weight: 930
url: /zh/java/com.aspose.pdf/defaultappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DefaultAppearance

```
public final class DefaultAppearance extends Object
```

描述字段的默认外观（字体、文字大小和颜色）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DefaultAppearance](#DefaultAppearance--) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance](#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance](#DefaultAppearance-java.lang.String-double-java.awt.Color-) | DefaultAppearance 的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFont](#getFont--) | 获取指定为文本默认的字体。 |
| [getFontName](#getFontName--) | 获取默认外观中的字体名称。 |
| [getFontResourceName](#getFontResourceName--) | 获取默认外观中的字体名称。 |
| [getFontSize](#getFontSize--) | 获取默认外观中的字体大小。 |
| [getText](#getText--) | 获取表示外观的 PDF 操作符列表。 |
| [getTextColor](#getTextColor--) | 获取默认外观中文本的颜色。 |
| [setFontName](#setFontName-java.lang.String-) | 获取默认外观中的字体名称。 |
| [setFontResourceName](#setFontResourceName-java.lang.String-) | 获取默认外观中的字体名称。 |
| [setFontSize](#setFontSize-double-) | 设置默认外观中的字体大小。 |
| [setTextColor](#setTextColor-java.awt.Color-) | 设置默认外观中文本的颜色。 |

### DefaultAppearance {#DefaultAppearance--}
```
public DefaultAppearance()
```

DefaultAppearance 的构造函数。

### DefaultAppearance {#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-}
DefaultAppearance 的构造函数。

### DefaultAppearance {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-}
DefaultAppearance 的构造函数。

### DefaultAppearance {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-}
DefaultAppearance 的构造函数。

### DefaultAppearance {#DefaultAppearance-java.lang.String-double-java.awt.Color-}
DefaultAppearance 的构造函数。

### getFont {#getFont--}
```
public Font getFont()
```

获取指定为文本默认的字体。

**Returns:**
字体值

### getFontName {#getFontName--}
```
public String getFontName()
```

获取默认外观中的字体名称。

**Returns:**
字符串值

### getFontResourceName {#getFontResourceName--}
```
public final String getFontResourceName()
```

获取默认外观中的字体名称。

**Returns:**
字符串值

### getFontSize {#getFontSize--}
```
public double getFontSize()
```

获取默认外观中的字体大小。

**Returns:**
字体大小

### getText {#getText--}
```
public String getText()
```

获取表示外观的 PDF 操作符列表。

**Returns:**
字符串值

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

获取默认外观中文本的颜色。

**Returns:**
Color 对象

### setFontName {#setFontName-java.lang.String-}
获取默认外观中的字体名称。

### setFontResourceName {#setFontResourceName-java.lang.String-}
获取默认外观中的字体名称。

### setFontSize {#setFontSize-double-}
```
public void setFontSize(double value)
```

设置默认外观中的字体大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 字体大小 |

### setTextColor {#setTextColor-java.awt.Color-}
设置默认外观中文本的颜色。
