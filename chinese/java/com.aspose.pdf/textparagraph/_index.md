---
title: TextParagraph
second_title: 用于 Java API 参考的 Aspose.PDF
description: 将文本段落表示为多行文本对象。
type: docs
weight: 380
url: /zh/java/com.aspose.pdf/textparagraph/
---
**遗产：**
java.lang.Object
```
public final class TextParagraph
```

将文本段落表示为多行文本对象。

--------------------

```
The example demonstrates how to create text paragraph object and append it to the Pdf page.


 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text paragraph
 TextParagraph paragraph = new TextParagraph();

 // set the paragraph rectangle
 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700));
 // set word wrapping options
 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords);
 // append string lines
 paragraph.appendLine("the quick brown fox jumps over the lazy dog");
 paragraph.appendLine("line2");
 paragraph.appendLine("line3");
 // append the paragraph to the Pdf page with the TextBuilder
 TextBuilder textBuilder = new TextBuilder(page);
 textBuilder.appendParagraph(paragraph);
 // save Pdf document
 doc.save(outFile);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextParagraph()](#TextParagraph--) | 创建 TextParagraph 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [appendLine(TextFragment line)](#appendLine-com.aspose.pdf.TextFragment-) | 附加带有文本状态参数的文本行。 |
| [appendLine(TextFragment line, TextState textState)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | 附加带有文本状态参数的文本行。 |
| [appendLine(TextFragment line, TextState textState, float lineSpacing)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | 附加带有文本状态参数的文本行 |
| [appendLine(String line)](#appendLine-java.lang.String-) | 追加文本行 |
| [appendLine(String line, TextState textState)](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | 附加带有文本状态参数的文本行。 |
| [appendLine(String line, TextState textState, float lineSpacing)](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | 附加带有文本状态参数的文本行 |
| [appendLine(String line, float lineSpacing)](#appendLine-java.lang.String-float-) | 追加文本行。 |
| [beginEdit()](#beginEdit--) | 开始编辑 TextParagraph。 |
| [endEdit()](#endEdit--) | 结束 TextParagraph 的编辑。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstLineIndent()](#getFirstLineIndent--) | 获取或设置后续行缩进值。 |
| [getFormattingOptions()](#getFormattingOptions--) | 获取格式化选项。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落矩形内文本的水平对齐方式。 |
| [getHyphenSymbol()](#getHyphenSymbol--) | 获取在断字过程中使用的连字符。 |
| [getMargin()](#getMargin--) | 获取填充。 |
| [getPosition()](#getPosition--) | 获取段落的位置。 |
| [getRectangle()](#getRectangle--) | 获取段落的矩形。 |
| [getRotation()](#getRotation--) | 获取或设置以度为单位的旋转角度。 |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | 获取后续行缩进值。 |
| [getTextRectangle()](#getTextRectangle--) | 获取放置在段落中的文本的矩形。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落 Rectangle 内文本的垂直对齐方式。 |
| [hashCode()](#hashCode--) |  |
| [isJustify()](#isJustify--) | 获取文本是否两端对齐的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本段落的背景颜色。 |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | 设置文本段落的背景模式 |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | 获取或设置后续行缩进值。 |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 设置格式选项。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落矩形内文本的水平对齐方式。 |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | 设置在断字过程中使用的连字符。 |
| [setJustify(boolean value)](#setJustify-boolean-) | 设置文本是否对齐的值。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置填充。 |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | 设置段落的旋转。 |
| [setOldCodeCompatibilityMode(boolean value)](#setOldCodeCompatibilityMode-boolean-) | 设置旧代码兼容模式 |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | 设置段落的位置。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | 设置段落的矩形。 |
| [setRotation(double value)](#setRotation-double-) | 获取或设置以度为单位的旋转角度。 |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | 设置后续行缩进值。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 为段落的 Rectangle 内的文本设置垂直对齐方式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextParagraph() {#TextParagraph--}
```
public TextParagraph()
```


创建 TextParagraph 对象。

### appendLine(TextFragment line) {#appendLine-com.aspose.pdf.TextFragment-}
```
public void appendLine(TextFragment line)
```


附加带有文本状态参数的文本行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | 新行的文本。 |

### appendLine(TextFragment line, TextState textState) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
```
public void appendLine(TextFragment line, TextState textState)
```


附加带有文本状态参数的文本行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | 新行的文本。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 新行的文本状态。 |

### appendLine(TextFragment line, TextState textState, float lineSpacing) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
```
public void appendLine(TextFragment line, TextState textState, float lineSpacing)
```


附加带有文本状态参数的文本行

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | 新行的文本。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 新行的文本状态。 |
| lineSpacing | float | 附加间距（0.0 是默认值，对应于默认文本行高）。间距值被添加到特定行的默认行间距，因此您可以指定 12.0 以在使用 12pt 字体绘制的文本行之后获得空行。 |

### appendLine(String line) {#appendLine-java.lang.String-}
```
public void appendLine(String line)
```


追加文本行

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | java.lang.String | 新行的文本。 |

### appendLine(String line, TextState textState) {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
```
public void appendLine(String line, TextState textState)
```


附加带有文本状态参数的文本行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | java.lang.String | 新行的文本。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 新行的文本状态。 |

### appendLine(String line, TextState textState, float lineSpacing) {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
```
public void appendLine(String line, TextState textState, float lineSpacing)
```


附加带有文本状态参数的文本行

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | java.lang.String | 新行的文本。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 新行的文本状态。 |
| lineSpacing | float | 附加间距（0.0 是默认值，对应于默认文本行高）。间距值被添加到特定行的默认行间距，因此您可以指定 12.0 以在使用 12pt 字体绘制的文本行之后获得空行。 |

### appendLine(String line, float lineSpacing) {#appendLine-java.lang.String-float-}
```
public void appendLine(String line, float lineSpacing)
```


追加文本行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | java.lang.String | 新行的文本。 |
| lineSpacing | float | 附加间距（0.0 是默认值，对应于默认文本行高）。间距值被添加到特定行的默认行间距，因此您可以指定 12.0 以在使用 12pt 字体绘制的文本行之后获得空行。 |

### beginEdit() {#beginEdit--}
```
public void beginEdit()
```


开始编辑 TextParagraph。

改进了 TextParagraph 填充的性能。在调用 EndEdit 方法之前，任何布局计算都会暂停。

请注意，方法调用不能嵌套。

### endEdit() {#endEdit--}
```
public void endEdit()
```


结束 TextParagraph 的编辑。

改进了 TextParagraph 填充的性能。在调用 EndEdit 方法之前，任何布局计算都会暂停。

请注意，方法调用不能嵌套。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFirstLineIndent() {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```


获取或设置后续行缩进值。如果设置为非零值，它比 FormattingOptions.SubsequentLinesIndent 值有优势。

**退货：**
float - 浮点值
### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


获取格式化选项。

**退货：**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - TextFormattingOptions 对象
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取段落矩形内文本的水平对齐方式。

HorizontalAlignment.None 等于 HorizontalAlignment.Left。

**退货：**
int - HorizontalAlignment 值
### getHyphenSymbol() {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```


获取在断字过程中使用的连字符。

连字符默认为“-”。要消除连字符绘制（换行过程仍然存在），请为 HyphenSymbol 设置空字符串 string.Empty。

**退货：**
java.lang.String - 字符串值
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getPosition() {#getPosition--}
```
public Position getPosition()
```


获取段落的位置。

**退货：**
[Position](../../com.aspose.pdf/position) - 位置值
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取段落的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getRotation() {#getRotation--}
```
public double getRotation()
```


获取或设置以度为单位的旋转角度。

**退货：**
双倍价值
### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


获取后续行缩进值。

**退货：**
float - 浮点值
### getTextRectangle() {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```


获取放置在段落中的文本的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取段落 Rectangle 内文本的垂直对齐方式。

**退货：**
int - VerticalAlignment 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isJustify() {#isJustify--}
```
public boolean isJustify()
```


获取文本是否两端对齐的值。

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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


设置文本段落的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色对象 |

### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


设置文本段落的背景模式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


获取或设置后续行缩进值。如果设置为非零值，它比 FormattingOptions.SubsequentLinesIndent 值有优势。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


设置格式选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | TextFormattingOptions 对象 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置段落矩形内文本的水平对齐方式。

HorizontalAlignment.None 等于 HorizontalAlignment.Left。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public void setHyphenSymbol(String value)
```


设置在断字过程中使用的连字符。

连字符默认为“-”。要消除连字符绘制（换行过程仍然存在），请为 HyphenSymbol 设置空字符串 string.Empty。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


设置文本是否对齐的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 值 |

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


设置段落的旋转。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | 矩阵对象 |

### setOldCodeCompatibilityMode(boolean value) {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```


设置旧代码兼容模式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


设置段落的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值 |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


设置段落的矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


获取或设置以度为单位的旋转角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


设置后续行缩进值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


为段落的 Rectangle 内的文本设置垂直对齐方式。

VerticalAlignment.None 等于 VerticalAlignment.Bottom。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 值 |

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
