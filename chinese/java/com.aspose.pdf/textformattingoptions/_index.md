---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本格式化选项"
type: docs
weight: 5080
url: /zh/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

表示文本格式化选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | 初始化 {@code TextFormattingOptions} 对象的新实例，使用未定义的换行模式。 |
| [TextFormattingOptions](#TextFormattingOptions-int-) | 初始化 {@code TextFormattingOptions} 对象的新实例，使用指定的换行模式。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | 获取或设置首行缩进值。 |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> 获取或设置在连字符处理过程中使用的连字符符号。 </p><hr> 若要消除连字符绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。 |
| [getLineSpacing](#getLineSpacing--) | 获取行间距模式。默认值为 LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | 获取或设置后续行缩进值。 |
| [getWrapMode](#getWrapMode--) | 获取换行模式。默认值为 WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | 获取或设置首行缩进值。 |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> 获取或设置在连字符处理过程中使用的连字符符号。 </p><hr> 若要消除连字符绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。 |
| [setLineSpacing](#setLineSpacing-int-) | 设置行间距模式。默认值为 LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | 获取或设置后续行缩进值。 |
| [setWrapMode](#setWrapMode-int-) | 设置换行模式。默认值为 WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

初始化 {@code TextFormattingOptions} 对象的新实例，使用未定义的换行模式。

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

初始化 {@code TextFormattingOptions} 对象的新实例，使用指定的换行模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wrapMode |  | 换行模式。@see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

获取或设置首行缩进值。

**Returns:**
float 值

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> 获取或设置在连字符处理过程中使用的连字符符号。 </p><hr> 若要消除连字符绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。

**Returns:**
字符串值

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

获取行间距模式。默认值为 LineSpacingMode.FontSize

**Returns:**
int 值 @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

获取或设置后续行缩进值。

**Returns:**
float 值

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

获取换行模式。默认值为 WordWrapMode.NoWrap

**Returns:**
WordWrapMode 值 @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

获取或设置首行缩进值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> 获取或设置在连字符处理过程中使用的连字符符号。 </p><hr> 若要消除连字符绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

设置行间距模式。默认值为 LineSpacingMode.FontSize

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

获取或设置后续行缩进值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

设置换行模式。默认值为 WordWrapMode.NoWrap

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | WordWrapMode 值 @see WordWrapMode |
