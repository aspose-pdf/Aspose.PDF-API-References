---
title: "FormattedText"
linktitle: "FormattedText"
second_title: "Aspose.PDF for Java API 参考"
description: "表示格式化文本的类。包含关于文本及其颜色、大小、样式的信息。"
type: docs
weight: 190
url: /zh/java/com.aspose.pdf.facades/formattedtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormattedText

```
public final class FormattedText extends Object
```

表示格式化文本的类。包含关于文本及其颜色、大小、样式的信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormattedText](#FormattedText--) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | 初始化 FormattedText。 |
| [FormattedText](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | 初始化 FormattedText。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addNewLineText](#addNewLineText-java.lang.String-) | 向 FormattedText 对象添加新行，并将 newLineText 设置为下一行的文本。 |
| [addNewLineText](#addNewLineText-java.lang.String-float-) | 向 FormattedText 对象添加新行，并将 newLineText 设置为下一行的文本。 |
| [getBackColor](#getBackColor--) | 内部 获取背景颜色 |
| [getFirstLine](#getFirstLine--) | 获取第一行 |
| [getFont](#getFont--) | 获取字体 |
| [getFontSize](#getFontSize--) | 获取字体大小 |
| [getText](#getText--) | 仅供内部使用 |
| [getTextColor](#getTextColor--) | 内部 获取文本颜色 |
| [getTextHeight](#getTextHeight--) | 获取文本的高度。 |
| [getTextWidth](#getTextWidth--) | 获取文本的宽度。 |
| [isCjk](#isCjk--) | 检查文本是否为 CJK（中文、日文或韩文）。 |
| [setCjkFontStyle](#setCjkFontStyle--) | 更改 CJK（中文、日文或韩文）字体的 FormattedText 字体样式。 |

### FormattedText {#FormattedText--}
```
public FormattedText()
```

初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
初始化 FormattedText。

### FormattedText {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
初始化 FormattedText。

### addNewLineText {#addNewLineText-java.lang.String-}
向 FormattedText 对象添加新行，并将 newLineText 设置为下一行的文本。

### addNewLineText {#addNewLineText-java.lang.String-float-}
向 FormattedText 对象添加新行，并将 newLineText 设置为下一行的文本。

### getBackColor {#getBackColor--}
```
public com.aspose.ms.System.Drawing.Color getBackColor()
```

内部 获取背景颜色

**Returns:**
颜色元素

### getFirstLine {#getFirstLine--}
```
public String getFirstLine()
```

获取第一行

**Returns:**
字符串值

### getFont {#getFont--}
```
public Font getFont()
```

获取字体

**Returns:**
字体元素

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

获取字体大小

**Returns:**
float 值

### getText {#getText--}
```
public com.aspose.ms.System.Collections.Generic.List< String > getText()
```

仅供内部使用

**Returns:**
内部对象

### getTextColor {#getTextColor--}
```
public com.aspose.ms.System.Drawing.Color getTextColor()
```

内部 获取文本颜色

**Returns:**
颜色元素

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

获取文本的高度。

**Returns:**
float 值

### getTextWidth {#getTextWidth--}
```
public float getTextWidth()
```

获取文本的宽度。

**Returns:**
float 值

### isCjk {#isCjk--}
```
public final boolean isCjk()
```

检查文本是否为 CJK（中文、日文或韩文）。

**Returns:**
如果文本是 CJK，则为真。否则为假。

### setCjkFontStyle {#setCjkFontStyle--}
```
public final void setCjkFontStyle()
```

更改 CJK（中文、日文或韩文）字体的 FormattedText 字体样式。
