---
title: FormattedText
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示格式化文本的类。
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.facades/formattedtext/
---
**遗产：**
java.lang.Object
```
public final class FormattedText
```

表示格式化文本的类。包含有关文本及其颜色、大小、样式的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormattedText()](#FormattedText--) | 初始化格式化文本。 |
| [FormattedText(String text)](#FormattedText-java.lang.String-) | 初始化格式化文本。 |
| [FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | 初始化格式化文本。 |
| [FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-float-) | 初始化格式化文本。 |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | 初始化格式化文本。 |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, Color backColor)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-) | 初始化格式化文本。 |
| [FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-) | 初始化格式化文本。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addNewLineText(String newLineText)](#addNewLineText-java.lang.String-) | 向 FormattedText 对象添加新行并将 newLineText 设置为下一行的文本。 |
| [addNewLineText(String newLineText, float lineSpacing)](#addNewLineText-java.lang.String-float-) | 向 FormattedText 对象添加新行并将 newLineText 设置为下一行的文本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackColor()](#getBackColor--) | Internal 获取返回颜色 |
| [getClass()](#getClass--) |  |
| [getFirstLine()](#getFirstLine--) | 获取第一行 |
| [getFont()](#getFont--) | 获取字体 |
| [getFontSize()](#getFontSize--) | 获取字体大小 |
| [getText()](#getText--) | 仅供内部使用 |
| [getTextColor()](#getTextColor--) | Internal 获取文字颜色 |
| [getTextHeight()](#getTextHeight--) | 获取文本的高度。 |
| [getTextWidth()](#getTextWidth--) | 获取文本的宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormattedText() {#FormattedText--}
```
public FormattedText()
```


初始化格式化文本。

### FormattedText(String text) {#FormattedText-java.lang.String-}
```
public FormattedText(String text)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 包含在 FormattedText 中的文本。 |

### FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 文本的颜色。 |
| fontStyle | int | 文本的样式。 |
| encodingType | int | 编码类型（EncodingType 枚举的值）。 |
| embedded | boolean | 如果将嵌入字体，则为真。 |
| textSize | float | 文本的大小。 |

### FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 文本的颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果将嵌入文本，则为真。 |
| textSize | float | 文本的大小。 |
| lineSpacing | float | 附加间距。 |

### FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| color | java.awt.Color | 文本的颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果将嵌入文本，则为真。 |
| textSize | float | 文本的大小。 |

### FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果 true 字体将被嵌入。 |
| textSize | float | 文本的大小。 |
| lineSpacing | float | 附加间距。 |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 文本的颜色。 |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 背景颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果 true 字体将被嵌入。 |
| textSize | float | 文本的大小。 |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容。 |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 文本的颜色。 |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | 背景颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果 true 字体将被嵌入。 |
| textSize | float | 文本的大小。 |
| lineSpacing | float | 附加间距。 |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| backColor | java.awt.Color | 背景颜色。 |
| textFont | int | 文本的字体。 |
| encoding | int | 文本的编码。 |
| embedded | boolean | 如果将嵌入字体，则为真。 |
| textSize | float | 文本的大小。 |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 字符串的文本内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| backColor | java.awt.Color | 背景的颜色。 |
| textFont | int | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果嵌入了真实字体。 |
| textSize | float | 文本的大小。 |
| lineSpacing | float | 附加间距。 |

### FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| backColor | java.awt.Color | 背景颜色。 |
| fontName | java.lang.String | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果 true 字体将被嵌入。 |
| fontSize | float | 文本的大小。 |

### FormattedText(String text, Color textColor, Color backColor) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-}
```
public FormattedText(String text, Color textColor, Color backColor)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| backColor | java.awt.Color | 背景颜色。 |

### FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


初始化格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容。 |
| textColor | java.awt.Color | 文本的颜色。 |
| fontName | java.lang.String | 文本的字体。 |
| textEncoding | int | 文本的编码。 |
| embedded | boolean | 如果 true 字体将被嵌入。 |
| fontSize | float | 文本的大小。 |

### addNewLineText(String newLineText) {#addNewLineText-java.lang.String-}
```
public void addNewLineText(String newLineText)
```


向 FormattedText 对象添加新行并将 newLineText 设置为下一行的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newLineText | java.lang.String | 新添加行的文本。 |

### addNewLineText(String newLineText, float lineSpacing) {#addNewLineText-java.lang.String-float-}
```
public void addNewLineText(String newLineText, float lineSpacing)
```


向 FormattedText 对象添加新行并将 newLineText 设置为下一行的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newLineText | java.lang.String | 新添加行的文本。 |
| lineSpacing | float | 行间距。 |

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
### getBackColor() {#getBackColor--}
```
public System.Drawing.Color getBackColor()
```


Internal 获取返回颜色

**退货：**
[Color](../../com.aspose.ms.system.drawing/color) - 颜色元素
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFirstLine() {#getFirstLine--}
```
public String getFirstLine()
```


获取第一行

**退货：**
java.lang.String - 字符串值
### getFont() {#getFont--}
```
public Font getFont()
```


获取字体

**退货：**
[Font](../../com.aspose.pdf/font) - 字体元素
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


获取字体大小

**退货：**
float - 浮点值
### getText() {#getText--}
```
public System.Collections.Generic.List<String> getText()
```


仅供内部使用

**退货：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 内部对象
### getTextColor() {#getTextColor--}
```
public System.Drawing.Color getTextColor()
```


Internal 获取文字颜色

**退货：**
[Color](../../com.aspose.ms.system.drawing/color) - 颜色元素
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


获取文本的高度。

**退货：**
float - 浮点值
### getTextWidth() {#getTextWidth--}
```
public float getTextWidth()
```


获取文本的宽度。

**退货：**
float - 浮点值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
