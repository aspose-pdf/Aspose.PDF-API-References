---
title: "TextState"
linktitle: "TextState"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本的文本状态"
type: docs
weight: 5340
url: /zh/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

表示文本的文本状态

## 字段

| 字段 | 描述 |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | 默认的制表符值，以默认字体的空格字符宽度计。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextState](#TextState--) | 创建文本状态对象。 |
| [TextState](#TextState-java.awt.Color-) | 创建文本状态对象。 |
| [TextState](#TextState-java.awt.Color-double-) | 创建文本状态对象。 |
| [TextState](#TextState-double-) | 创建带有字体大小指定的文本状态对象。 |
| [TextState](#TextState-java.lang.String-) | 创建文本状态对象。 |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | 创建文本状态对象。 |
| [TextState](#TextState-java.lang.String-double-) | 创建文本状态对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> 从另一个 textState 应用设置 </p> <hr> <p> 仅复制那些已显式更改的属性。 </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | 计算矩形的字体大小。 |
| [getBackgroundColor](#getBackgroundColor--) | <p> 获取文本的背景颜色。 </p> <hr> <p> 请注意，该值不会作为文档中的文本特性保留。BackgroundColor 属性的 getter 在对象之前已通过 BackgroundColor setter 显式设置时有效。该属性在运行时的当前生成/修改过程中使用。 </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | 获取文本的字符间距。 |
| [getCoordinateOrigin](#getCoordinateOrigin--) | 获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。 |
| [getFont](#getFont--) | 获取文本的字体。 |
| [getfontSize](#getfontSize--) | 表示 getfontSize 方法 |
| [getFontSize](#getFontSize--) | 获取文本的字体大小。 |
| [getFontStyle](#getFontStyle--) | 设置文本的字体样式。 |
| [getForegroundColor](#getForegroundColor--) | 获取文本的前景颜色。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> 获取文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅在新文档生成场景中有效。 </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | 获取文本的水平缩放。 |
| [getLineSpacing](#getLineSpacing--) | <p> 获取文本的行间距。 </p> |
| [getRenderingMode](#getRenderingMode--) | 获取或设置文本的渲染模式。 |
| [getStrokingColor](#getStrokingColor--) | 获取或设置文本的前景色。 |
| [getTabTag](#getTabTag--) | <p> 您可以在文本中放置此标签以声明制表符。 </p> <hr> <p> 它仅在与 {@code TabStops} 配合使用时生效。 </p> |
| [getTextHeight](#getTextHeight--) | 获取文本高度。 |
| [getWordSpacing](#getWordSpacing--) | 获取文本的字间距。 |
| [isInvisible](#isInvisible--) | 获取文本的不可见性。这基本上反映了 {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) 状态，除了一些特殊情况（如裁剪）。 |
| [isStrikeOut](#isStrikeOut--) | 获取文本的删除线，由 {@code TextFragment} 对象表示 |
| [isSubscript](#isSubscript--) | 获取或设置文本的下标。 |
| [isSuperscript](#isSuperscript--) | 获取文本的上标。 |
| [isUnderline](#isUnderline--) | 获取文本的下划线，由 {@code TextFragment} 对象表示 |
| [measureHeight](#measureHeight-char-) | 测量字符高度。 |
| [measureString](#measureString-java.lang.String-) | 测量字符串。 |
| [measureString](#measureString-java.lang.String-boolean-) | <p> 测量字符串。 </p> <hr> <p> insideLine 表示字符串未结束。若只测量了整个字符串的一部分，则 insideLine 应为 true。若测量了整个字符串，则 insideLine 应为 false。换句话说：当 insideLine = true 时，仅考虑字符宽度。若 insideLine = false，则不考虑额外的变换，字符串结束会被正确处理——斜体变换会被考虑在内。 </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本的背景色。 |
| [setCharacterSpacing](#setCharacterSpacing-float-) | 设置文本的字符间距。 |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | 获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | 获取文本的字体。 |
| [setFontSize](#setFontSize-float-) | 设置文本的字体大小。 |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | 设置文本的字体大小并抑制更新。 |
| [setFontStyle](#setFontStyle-int-) | 设置文本的字体样式。 |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | 获取文本的字体并抑制更新。 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | 设置文本的前景色。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> 设置文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅在新文档生成场景中有效。 </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | 设置文本的水平缩放。 |
| [setInvisible](#setInvisible-boolean-) | 设置文本的不可见性。这基本上反映了 {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) 状态，除了一些特殊情况（如裁剪）。 |
| [setLineSpacing](#setLineSpacing-float-) | <p> 设置文本的行间距。 </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | 获取或设置文本的渲染模式。 |
| [setStrikeOut](#setStrikeOut-boolean-) | 设置文本的删除线，由 {@code TextFragment} 对象表示 |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | 获取或设置文本的前景色。 |
| [setSubscript](#setSubscript-boolean-) | 获取或设置文本的下标。 |
| [setSuperscript](#setSuperscript-boolean-) | 设置文本的上标。 |
| [setUnderline](#setUnderline-boolean-) | 为文本设置下划线，由 {@code TextFragment} 对象表示 |
| [setWordSpacing](#setWordSpacing-float-) | 设置文本的字间距。 |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

默认的制表符值，以默认字体的空格字符宽度计。

### TextState {#TextState--}
```
public TextState()
```

创建文本状态对象。

### TextState {#TextState-java.awt.Color-}
创建文本状态对象。

### TextState {#TextState-java.awt.Color-double-}
创建文本状态对象。

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

创建带有字体大小指定的文本状态对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSize |  | 字体大小。 |

### TextState {#TextState-java.lang.String-}
创建文本状态对象。

### TextState {#TextState-java.lang.String-boolean-boolean-}
创建文本状态对象。

### TextState {#TextState-java.lang.String-double-}
创建文本状态对象。

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> 从另一个 textState 应用设置 </p> <hr> <p> 仅复制那些已显式更改的属性。 </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
计算矩形的字体大小。

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> 获取文本的背景颜色。 </p> <hr> <p> 请注意，该值不会作为文档中的文本特性保留。BackgroundColor 属性的 getter 在对象之前已通过 BackgroundColor setter 显式设置时有效。该属性在运行时的当前生成/修改过程中使用。 </p>

**Returns:**
颜色值

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

获取文本的字符间距。

**Returns:**
float 值

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。

**Returns:**
CoordinateOrigin 元素

### getFont {#getFont--}
```
public Font getFont()
```

获取文本的字体。

**Returns:**
Font 对象

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

表示 getfontSize 方法

**Returns:**
float 值

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

获取文本的字体大小。

**Returns:**
float 值

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

设置文本的字体样式。

**Returns:**
FontStyles 元素 @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

获取文本的前景颜色。

**Returns:**
颜色值

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> 获取文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅在新文档生成场景中有效。 </p>

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

获取文本的水平缩放。

**Returns:**
float 值

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> 获取文本的行间距。 </p>

**Returns:**
float value <hr> <p> 注意，该值不会作为文档中的文本特性保存。LineSpacing 属性的 getter 在对象已通过 LineSpacing setter 明确设置的情况下工作。该属性在运行时的当前生成/修改过程上下文中使用。 </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

获取或设置文本的渲染模式。

**Returns:**
TextRenderingMode 元素 @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

获取或设置文本的前景色。

**Returns:**
Color 实例

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> 您可以在文本中放置此标签以声明制表符。 </p> <hr> <p> 它仅在与 {@code TabStops} 配合使用时生效。 </p>

**Returns:**
字符串值 "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

获取文本高度。

**Returns:**
float 值

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

获取文本的字间距。

**Returns:**
float 值

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

获取文本的不可见性。这基本上反映了 {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) 状态，除了一些特殊情况（如裁剪）。

**Returns:**
布尔值

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

获取文本的删除线，由 {@code TextFragment} 对象表示

**Returns:**
布尔值

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

获取或设置文本的下标。

**Returns:**
布尔值

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

获取文本的上标。

**Returns:**
布尔值

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

获取文本的下划线，由 {@code TextFragment} 对象表示

**Returns:**
布尔值

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

测量字符高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字符 |  | 要测量的字符。 |

**Returns:**
如果能够从字体获取，则为字符的高度；否则为 0。

### measureString {#measureString-java.lang.String-}
测量字符串。

### measureString {#measureString-java.lang.String-boolean-}
<p> 测量字符串。 </p> <hr> <p> insideLine 表示字符串未结束。若只测量了整个字符串的一部分，则 insideLine 应为 true。若测量了整个字符串，则 insideLine 应为 false。换句话说：当 insideLine = true 时，仅考虑字符宽度。若 insideLine = false，则不考虑额外的变换，字符串结束会被正确处理——斜体变换会被考虑在内。 </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置文本的背景色。

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

设置文本的字符间距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。

### setFont {#setFont-com.aspose.pdf.Font-}
获取文本的字体。

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

设置文本的字体大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

设置文本的字体大小并抑制更新。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

设置文本的字体样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | FontStyles 值 @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
获取文本的字体并抑制更新。

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
设置文本的前景色。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> 设置文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅在新文档生成场景中有效。 </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

设置文本的水平缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

设置文本的不可见性。这基本上反映了 {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) 状态，除了一些特殊情况（如裁剪）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> 设置文本的行间距。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float value <hr> <p> 注意，该值不会作为文档中的文本特性保存。LineSpacing 属性的 getter 在对象已通过 LineSpacing setter 明确设置的情况下工作。该属性在运行时的当前生成/修改过程上下文中使用。 </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
获取或设置文本的渲染模式。

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

设置文本的删除线，由 {@code TextFragment} 对象表示

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
获取或设置文本的前景色。

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

获取或设置文本的下标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

设置文本的上标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

为文本设置下划线，由 {@code TextFragment} 对象表示

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

设置文本的字间距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |
