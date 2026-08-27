---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示文本段落作为多行文本对象。 </p> <hr> <pre> 示例演示如何创建文本段落对象并将其附加到 Pdf 页面。 Document doc."
type: docs
weight: 5200
url: /zh/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> 表示文本段落为多行文本对象。 </p> <hr> <pre> 示例演示如何创建文本段落对象并将其追加到 PDF 页面。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本段落 TextParagraph paragraph = new TextParagraph(); // 设置段落矩形 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // 设置换行选项 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // 追加字符串行 paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // 使用 TextBuilder 将段落追加到 PDF 页面 TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // 保存 PDF 文档 doc.save(outFile); </pre>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextParagraph](#TextParagraph--) | 创建 {@code TextParagraph} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | 追加文本行 |
| [appendLine](#appendLine-java.lang.String-float-) | 追加文本行。 |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | 追加带有文本状态参数的文本行。 |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | 追加带有文本状态参数的文本行 |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | 追加带有文本状态参数的文本行。 |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | 追加带有文本状态参数的文本行。 |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | 追加带有文本状态参数的文本行 |
| [beginEdit](#beginEdit--) | 开始编辑 TextParagraph。 <p> 提高 TextParagraph 填充的性能。任何布局计算将在调用 EndEdit 方法之前被挂起。 <p> 注意，方法调用不能嵌套。 </p> |
| [endEdit](#endEdit--) | 结束编辑 TextParagraph。 <p> 提高 TextParagraph 填充的性能。任何布局计算将在调用 EndEdit 方法后被挂起。 <p> 注意，方法调用不能嵌套。 </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | 获取或设置后续行的缩进值。如果设置为非零值，则相对于 FormattingOptions.SubsequentLinesIndent 值具有优势。 |
| [getFormattingOptions](#getFormattingOptions--) | 获取格式化选项。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取段落的矩形内文本的水平对齐方式。HorizontalAlignment.None 等同于 HorizontalAlignment.Left。 |
| [getHyphenSymbol](#getHyphenSymbol--) | 获取用于连字符处理的连字符符号。默认的连字符符号是 "-"。若要消除连字符的绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。 |
| [getMargin](#getMargin--) | 获取内边距。 |
| [getPosition](#getPosition--) | 获取段落的位置。 |
| [getRectangle](#getRectangle--) | 获取段落的矩形。 |
| [getRotation](#getRotation--) | 获取或设置以度为单位的旋转角度。 |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | 获取后续行的缩进值。 |
| [getTextRectangle](#getTextRectangle--) | 获取放置在段落中的文本的矩形。 |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> 获取段落的 {@code Rectangle} 内文本的垂直对齐方式。 </p> |
| [isJustify](#isJustify--) | 获取文本是否两端对齐的值。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本段落的背景颜色。 |
| [setBackgroundMode](#setBackgroundMode-int-) | 设置文本段落的背景模式 |
| [setFirstLineIndent](#setFirstLineIndent-float-) | 获取或设置后续行的缩进值。如果设置为非零值，则相对于 FormattingOptions.SubsequentLinesIndent 值具有优势。 |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 设置格式选项。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置段落矩形内文本的水平对齐方式。HorizontalAlignment.None 等同于 HorizontalAlignment.Left。 |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | 设置用于连字符处理的连字符符号。默认的连字符符号是 "-"。若要消除连字符的绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。 |
| [setJustify](#setJustify-boolean-) | 设置文本是否两端对齐的值。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 设置内边距。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 设置段落的旋转。 |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | 设置旧代码兼容模式 |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | 设置段落的位置。 |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 设置段落的矩形。 |
| [setRotation](#setRotation-double-) | 获取或设置以度为单位的旋转角度。 |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | 设置后续行的缩进值。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置段落的 {@code Rectangle} 内文本的垂直对齐方式。VerticalAlignment.None 等同于 VerticalAlignment.Bottom。 |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

创建 {@code TextParagraph} 对象。

### appendLine {#appendLine-java.lang.String-}
追加文本行

### appendLine {#appendLine-java.lang.String-float-}
追加文本行。

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
追加带有文本状态参数的文本行。

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
追加带有文本状态参数的文本行

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
追加带有文本状态参数的文本行。

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
追加带有文本状态参数的文本行。

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
追加带有文本状态参数的文本行

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

开始编辑 TextParagraph。 <p> 提高 TextParagraph 填充的性能。任何布局计算将在调用 EndEdit 方法之前被挂起。 <p> 注意，方法调用不能嵌套。 </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

结束编辑 TextParagraph。 <p> 提高 TextParagraph 填充的性能。任何布局计算将在调用 EndEdit 方法后被挂起。 <p> 注意，方法调用不能嵌套。 </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

获取或设置后续行的缩进值。如果设置为非零值，则相对于 FormattingOptions.SubsequentLinesIndent 值具有优势。

**Returns:**
float 值

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

获取格式化选项。

**Returns:**
TextFormattingOptions 对象

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取段落的矩形内文本的水平对齐方式。HorizontalAlignment.None 等同于 HorizontalAlignment.Left。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

获取用于连字符处理的连字符符号。默认的连字符符号是 "-"。若要消除连字符的绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。

**Returns:**
字符串值

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

获取内边距。

**Returns:**
MarginInfo 值

### getPosition {#getPosition--}
```
public Position getPosition()
```

获取段落的位置。

**Returns:**
位置值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取段落的矩形。

**Returns:**
Rectangle 对象

### getRotation {#getRotation--}
```
public double getRotation()
```

获取或设置以度为单位的旋转角度。

**Returns:**
double 值

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

获取后续行的缩进值。

**Returns:**
float 值

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

获取放置在段落中的文本的矩形。

**Returns:**
Rectangle 对象

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> 获取段落的 {@code Rectangle} 内文本的垂直对齐方式。 </p>

**Returns:**
VerticalAlignment 值 @see VerticalAlignment <hr> <p> VerticalAlignment.None 等同于 VerticalAlignment.Bottom。 </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

获取文本是否两端对齐的值。

**Returns:**
布尔值

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置文本段落的背景颜色。

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

设置文本段落的背景模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

获取或设置后续行的缩进值。如果设置为非零值，则相对于 FormattingOptions.SubsequentLinesIndent 值具有优势。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
设置格式选项。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置段落矩形内文本的水平对齐方式。HorizontalAlignment.None 等同于 HorizontalAlignment.Left。

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
设置用于连字符处理的连字符符号。默认的连字符符号是 "-"。若要消除连字符的绘制（换行过程仍然保留），请将 HyphenSymbol 设置为空字符串 string.Empty。

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

设置文本是否两端对齐的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
设置内边距。

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
设置段落的旋转。

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

设置旧代码兼容模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPosition {#setPosition-com.aspose.pdf.Position-}
设置段落的位置。

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
设置段落的矩形。

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

获取或设置以度为单位的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

设置后续行的缩进值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置段落的 {@code Rectangle} 内文本的垂直对齐方式。VerticalAlignment.None 等同于 VerticalAlignment.Bottom。
