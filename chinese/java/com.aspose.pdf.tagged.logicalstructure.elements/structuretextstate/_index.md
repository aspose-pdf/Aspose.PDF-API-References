---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本结构元素和标记内容（ITextElement、ITaggedContent）的文本状态设置。"
type: docs
weight: 120
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

表示文本结构元素和标记内容（ITextElement、ITaggedContent）的文本状态设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructureTextState](#StructureTextState--) | 默认构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [createTextState](#createTextState--) | 创建文本状态 |
| [getBackgroundColor](#getBackgroundColor--) | 获取或设置文本的背景颜色。可以为 null。使用 null 可从父结构元素继承 {@code BackgroundColor} 属性。 |
| [getCharacterSpacing](#getCharacterSpacing--) | 获取或设置文本的字符间距。可以为 null。使用 null 可从父结构元素继承 {@code CharacterSpacing} 属性。 |
| [getFont](#getFont--) | 获取或设置文本的字体。可以为 null。使用 null 可从父结构元素继承 {@code Font} 属性。 |
| [getFontSize](#getFontSize--) | 获取或设置文本的字体大小。可以为 null。使用 null 可从父结构元素继承 {@code FontSize} 属性。 |
| [getFontStyle](#getFontStyle--) | 获取或设置文本的字体样式。可以为 null。使用 null 可从父结构元素继承 {@code FontStyle} 属性。 |
| [getForegroundColor](#getForegroundColor--) | 获取或设置文本的前景颜色。可以为 null。使用 null 可从父结构元素继承 {@code ForegroundColor} 属性。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取或设置段落的水平对齐方式 |
| [getHorizontalScaling](#getHorizontalScaling--) | 获取或设置文本的水平缩放。可以为 null。使用 null 可从父结构元素继承 {@code HorizontalScaling} 属性。 |
| [getLineSpacing](#getLineSpacing--) | 获取或设置文本的行间距。可以为 null。使用 null 可从父结构元素继承 {@code LineSpacing} 属性。 |
| [getMarginInfo](#getMarginInfo--) | 获取或设置块结构元素的边距。 |
| [getStrikeOut](#getStrikeOut--) | 获取或设置文本的删除线。可以为 null。使用 null 可从父结构元素继承 {@code StrikeOut} 属性。 |
| [getSubscript](#getSubscript--) | 获取或设置文本的下标。可以为 null。使用 null 可从父结构元素继承 {@code Subscript} 属性。 |
| [getSuperscript](#getSuperscript--) | 获取或设置文本的上标。可以为 null。使用 null 可从父结构元素继承 {@code Superscript} 属性。 |
| [getUnderline](#getUnderline--) | 获取或设置文本的下划线。可以为 null。使用 null 可从父结构元素继承 {@code Underline} 属性。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取或设置段落的垂直对齐方式 |
| [getWordSpacing](#getWordSpacing--) | 获取或设置文本的字间距。可以为 null。使用 null 可从父结构元素继承 {@code WordSpacing} 属性。 |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。 |
| [isInLineParagraph](#isInLineParagraph--) | 获取或设置段落是否为内联。默认值为 false。 |
| [isInNewPage](#isInNewPage--) | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。 |
| [isKeptWithNext](#isKeptWithNext--) | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页。默认值为 false。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置文本的背景颜色。可以为 null。使用 null 可从父结构元素继承 {@code BackgroundColor} 属性。 |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | 获取或设置文本的字符间距。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | 获取或设置文本的字体。可以为 null。使用 null 可从父结构元素继承 {@code Font} 属性。 |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | 获取或设置文本的字体大小。 |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | 获取或设置文本的字体样式。 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | 获取或设置文本的前景颜色。可以为 null。使用 null 可从父结构元素继承 {@code ForegroundColor} 属性。 |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | 获取或设置文本的水平缩放。 |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | 获取或设置文本的行间距。 |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | 获取或设置块结构元素的边距。 |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | 获取或设置文本的删除线。 |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | 获取或设置文本的下标。 |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | 获取或设置文本的上标。 |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | 获取或设置文本的下划线。 |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | 获取或设置文本的字间距。 |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | 更新元素 |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

默认构造函数

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

创建文本状态

**Returns:**
TextState 实例

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取或设置文本的背景颜色。可以为 null。使用 null 可从父结构元素继承 {@code BackgroundColor} 属性。

**Returns:**
Color 实例

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

获取或设置文本的字符间距。可以为 null。使用 null 可从父结构元素继承 {@code CharacterSpacing} 属性。

**Returns:**
浮点数组

### getFont {#getFont--}
```
public final Font getFont()
```

获取或设置文本的字体。可以为 null。使用 null 可从父结构元素继承 {@code Font} 属性。

**Returns:**
字体实例

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

获取或设置文本的字体大小。可以为 null。使用 null 可从父结构元素继承 {@code FontSize} 属性。

**Returns:**
浮点数组

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

获取或设置文本的字体样式。可以为 null。使用 null 可从父结构元素继承 {@code FontStyle} 属性。

**Returns:**
整数数组

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

获取或设置文本的前景颜色。可以为 null。使用 null 可从父结构元素继承 {@code ForegroundColor} 属性。

**Returns:**
Color 实例

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

获取或设置段落的水平对齐方式

**Returns:**
HorizontalAlignment 元素

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

获取或设置文本的水平缩放。可以为 null。使用 null 可从父结构元素继承 {@code HorizontalScaling} 属性。

**Returns:**
浮点数组

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

获取或设置文本的行间距。可以为 null。使用 null 可从父结构元素继承 {@code LineSpacing} 属性。

**Returns:**
浮点数组

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

获取或设置块结构元素的边距。

**Returns:**
MarginInfo 实例 @deprecated 使用 IAdjustPosition.AdjustPosition(PositionSettings positionSettings) 方法来设置位置设置

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

获取或设置文本的删除线。可以为 null。使用 null 可从父结构元素继承 {@code StrikeOut} 属性。

**Returns:**
布尔数组

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

获取或设置文本的下标。可以为 null。使用 null 可从父结构元素继承 {@code Subscript} 属性。

**Returns:**
布尔数组

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

获取或设置文本的上标。可以为 null。使用 null 可从父结构元素继承 {@code Superscript} 属性。

**Returns:**
布尔数组

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

获取或设置文本的下划线。可以为 null。使用 null 可从父结构元素继承 {@code Underline} 属性。

**Returns:**
布尔数组

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

获取或设置段落的垂直对齐方式

**Returns:**
VerticalAlignment 元素

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

获取或设置文本的字间距。可以为 null。使用 null 可从父结构元素继承 {@code WordSpacing} 属性。

**Returns:**
浮点数组

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。

**Returns:**
布尔值

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

获取或设置段落是否为内联。默认值为 false。

**Returns:**
布尔值

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。

**Returns:**
布尔值

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页。默认值为 false。

**Returns:**
布尔值

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取或设置文本的背景颜色。可以为 null。使用 null 可从父结构元素继承 {@code BackgroundColor} 属性。

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
获取或设置文本的字符间距。

### setFont {#setFont-com.aspose.pdf.Font-}
获取或设置文本的字体。可以为 null。使用 null 可从父结构元素继承 {@code Font} 属性。

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
获取或设置文本的字体大小。

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
获取或设置文本的字体样式。

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
获取或设置文本的前景颜色。可以为 null。使用 null 可从父结构元素继承 {@code ForegroundColor} 属性。

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
获取或设置文本的水平缩放。

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
获取或设置文本的行间距。

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
获取或设置块结构元素的边距。

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
获取或设置文本的删除线。

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
获取或设置文本的下标。

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
获取或设置文本的上标。

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
获取或设置文本的下划线。

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
获取或设置文本的字间距。

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
更新元素
