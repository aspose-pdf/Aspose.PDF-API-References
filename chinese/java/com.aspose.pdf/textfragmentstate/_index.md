---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示文本片段的文本状态。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象更改文本的颜色和字体大小。 // Open.</pre>"
type: docs
weight: 5150
url: /zh/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> 表示文本片段的文本状态。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象更改文本的颜色和字体大小。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get(1).accept(absorber); // 更改第一次文本出现的前景色 absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // 更改第一次文本出现的字体大小 absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 提供了一种更改文本以下属性的方法： font ({@code TextFragmentState.Font} property) font size ({@code TextFragmentState.FontSize} property) font style ( {@code TextFragmentState.FontStyle} property) foreground color ( {@code TextFragmentState.ForegroundColor} property) background color ( {@code TextFragmentState.BackgroundColor} property) </p> <p> 请注意，修改 {@code TextFragmentState} 属性可能会更改内部 {@code TextFragment.Segments} 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的需求是保持 {@code TextFragment.Segments} 集合不变，请单独更改内部段。 </p> @see TextFragmentAbsorber @see IDocument

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | 使用指定的 {@code TextFragment} 对象初始化 {@code TextFragmentState} 对象的新实例。此 {@code TextFragmentState} 初始化不受支持。TextFragmentState 仅在 {@code TextFragment.TextState} 属性中可用。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> 应用来自另一个 textState 的设置 </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | 应用来自另一个 textState 的设置 |
| [getBackgroundColor](#getBackgroundColor--) | 设置文本的背景颜色，由 {@code TextFragment} 对象表示 |
| [getCharacterSpacing](#getCharacterSpacing--) | 获取文本的字符间距，由 {@code TextFragment} 对象表示。 |
| [getCoordinateOrigin](#getCoordinateOrigin--) | 获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。 |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | 获取文本矩形边框绘制标志。 |
| [getFont](#getFont--) | 获取文本的字体，由 {@code TextFragment} 对象表示 |
| [getFontSize](#getFontSize--) | 获取文本的字体大小，由 {@code TextFragment} 对象表示 |
| [getFontStyle](#getFontStyle--) | 设置文本的字体样式，由 {@code TextFragment} 对象表示 |
| [getForegroundColor](#getForegroundColor--) | 获取文本的前景色，由 {@code TextFragment} 对象表示 |
| [getFormattingOptions](#getFormattingOptions--) | 获取或设置格式选项。仅在生成器场景中设置这些选项才会生效。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> 获取文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextFragmentState.VerticalAlignment 属性仅在新文档生成场景中有效。 </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | 获取文本的水平缩放比例，由 {@code TextFragment} 对象表示。 |
| [getLineSpacing](#getLineSpacing--) | <p> 获取文本的行间距。 </p> |
| [getRenderingMode](#getRenderingMode--) | 获取或设置文本的渲染模式。 |
| [getRotation](#getRotation--) | 获取或设置以度为单位的旋转角度。 |
| [getStrokingColor](#getStrokingColor--) | 获取或设置 {@code TextFragment} 渲染的颜色描边操作（描边文本，矩形边框） |
| [getTabStops](#getTabStops--) | <p> 获取文本的制表位。 </p> <hr> <p> 注意，Tabstops 属性仅在新文档生成场景中有效。Tabstops 可以在 {@code TextFragment} 初始化期间添加。Tabstops 必须在文本之前构建。 </p> |
| [getTextHeight](#getTextHeight--) | 获取文本高度，由 {@code TextFragment} 对象表示 |
| [getWordSpacing](#getWordSpacing--) | 获取文本的字间距。 |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | 检查输入字符串是否可以放置在定义的矩形内。 |
| [isInvisible](#isInvisible--) | 获取文本的不可见性。 |
| [isStrikeOut](#isStrikeOut--) | 获取或设置文本的删除线，由 {@link TextFragment} 对象表示 |
| [isSubscript](#isSubscript--) | 获取或设置文本的下标，由 {@code TextFragment} 对象表示。 |
| [isSuperscript](#isSuperscript--) | 获取或设置文本的上标，由 {@code TextFragment} 对象表示。 |
| [isUnderline](#isUnderline--) | 获取或设置文本的下划线，由 {@link TextFragment} 对象表示 |
| [measureHeight](#measureHeight-char-) | 测量字符高度。 |
| [measureString](#measureString-java.lang.String-) | 测量字符串。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本的背景颜色，由 TextFragment 对象表示 |
| [setCharacterSpacing](#setCharacterSpacing-float-) | 设置文本的字符间距，由 {@code TextFragment} 对象表示。 |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | 获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。 |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | 设置是否绘制文本矩形边框的标志。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | 设置文本的字体，由 {@code TextFragment} 对象表示 |
| [setFontSize](#setFontSize-float-) | 设置文本的字体大小，由 {@code TextFragment} 对象表示 |
| [setFontStyle](#setFontStyle-int-) | 设置文本的字体样式，由 {@link TextFragment} 对象表示 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | 设置文本的前景颜色，由 {@code TextFragment} 对象表示 |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 获取或设置格式选项。仅在生成器场景中设置这些选项才会生效。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> 设置文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。注意，TextFragmentState.VerticalAlignment 属性仅在新文档生成场景中有效。 </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | 设置文本的水平缩放，由 {@code TextFragment} 对象表示。 |
| [setInvisible](#setInvisible-boolean-) | 设置文本的不可见性。 |
| [setLineSpacing](#setLineSpacing-float-) | <p> 设置文本的行间距。 </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | 获取或设置文本的渲染模式。 |
| [setRotation](#setRotation-double-) | 获取或设置以度为单位的旋转角度。 |
| [setStrikeOut](#setStrikeOut-boolean-) | 设置文本的删除线，由 {@code TextFragment} 对象表示 |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | 获取或设置 {@code TextFragment} 渲染的颜色描边操作（描边文本，矩形边框） |
| [setSubscript](#setSubscript-boolean-) | 获取或设置文本的下标，由 {@code TextFragment} 对象表示。 |
| [setSuperscript](#setSuperscript-boolean-) | 获取或设置文本的上标，由 {@code TextFragment} 对象表示。 |
| [setUnderline](#setUnderline-boolean-) | 为文本设置下划线，由 {@code TextFragment} 对象表示 |
| [setWordSpacing](#setWordSpacing-float-) | 设置文本的字间距。 |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
使用指定的 {@code TextFragment} 对象初始化 {@code TextFragmentState} 对象的新实例。此 {@code TextFragmentState} 初始化不受支持。TextFragmentState 仅在 {@code TextFragment.TextState} 属性中可用。

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> 应用来自另一个 textState 的设置 </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
应用来自另一个 textState 的设置

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

设置文本的背景颜色，由 {@code TextFragment} 对象表示

**Returns:**
值 Color 对象

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

获取文本的字符间距，由 {@code TextFragment} 对象表示。

**Returns:**
float 值

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。

**Returns:**
CoordinateOrigin 元素

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

获取文本矩形边框绘制标志。

**Returns:**
布尔值

### getFont {#getFont--}
```
public Font getFont()
```

获取文本的字体，由 {@code TextFragment} 对象表示

**Returns:**
字体值

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

获取文本的字体大小，由 {@code TextFragment} 对象表示

**Returns:**
float 值

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

设置文本的字体样式，由 {@code TextFragment} 对象表示

**Returns:**
FontStyles 元素 @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

获取文本的前景色，由 {@code TextFragment} 对象表示

**Returns:**
Color 对象

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

获取或设置格式选项。仅在生成器场景中设置这些选项才会生效。

**Returns:**
TextFormattingOptions 实例

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> 获取文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。请注意，TextFragmentState.VerticalAlignment 属性仅在新文档生成场景中有效。 </p>

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

获取文本的水平缩放比例，由 {@code TextFragment} 对象表示。

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
TextRenderingMode 元素

### getRotation {#getRotation--}
```
public double getRotation()
```

获取或设置以度为单位的旋转角度。

**Returns:**
double 值

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

获取或设置 {@code TextFragment} 渲染的颜色描边操作（描边文本，矩形边框）

**Returns:**
Color 实例

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> 获取文本的制表位。 </p> <hr> <p> 注意，Tabstops 属性仅在新文档生成场景中有效。Tabstops 可以在 {@code TextFragment} 初始化期间添加。Tabstops 必须在文本之前构建。 </p>

**Returns:**
TabStops 对象

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

获取文本高度，由 {@code TextFragment} 对象表示

**Returns:**
float 值

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

获取文本的字间距。

**Returns:**
float 值

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
检查输入字符串是否可以放置在定义的矩形内。

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

获取文本的不可见性。

**Returns:**
布尔值

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

获取或设置文本的删除线，由 {@link TextFragment} 对象表示

**Returns:**
布尔值

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

获取或设置文本的下标，由 {@code TextFragment} 对象表示。

**Returns:**
布尔值

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

获取或设置文本的上标，由 {@code TextFragment} 对象表示。

**Returns:**
value 布尔值

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

获取或设置文本的下划线，由 {@link TextFragment} 对象表示

**Returns:**
布尔值

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置文本的背景颜色，由 TextFragment 对象表示

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

设置文本的字符间距，由 {@code TextFragment} 对象表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 BaseLine 作为 CoordinateOrigin，以获得更好的文本渲染。

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

设置是否绘制文本矩形边框的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFont {#setFont-com.aspose.pdf.Font-}
设置文本的字体，由 {@code TextFragment} 对象表示

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

设置文本的字体大小，由 {@code TextFragment} 对象表示

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

设置文本的字体样式，由 {@link TextFragment} 对象表示

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
设置文本的前景颜色，由 {@code TextFragment} 对象表示

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
获取或设置格式选项。仅在生成器场景中设置这些选项才会生效。

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> 设置文本的水平对齐方式。 </p> <hr> <p> HorizontalAlignment.None 等同于 HorizontalAlignment.Left。注意，TextFragmentState.VerticalAlignment 属性仅在新文档生成场景中有效。 </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

设置文本的水平缩放，由 {@code TextFragment} 对象表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

设置文本的不可见性。

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

获取或设置以度为单位的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

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
获取或设置 {@code TextFragment} 渲染的颜色描边操作（描边文本，矩形边框）

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

获取或设置文本的下标，由 {@code TextFragment} 对象表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

获取或设置文本的上标，由 {@code TextFragment} 对象表示。

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
