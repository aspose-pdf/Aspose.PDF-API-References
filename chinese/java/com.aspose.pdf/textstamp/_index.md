---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本印章。"
type: docs
weight: 5320
url: /zh/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

表示文本印章。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | 使用 formattedText 对象初始化 {@code TextStamp} 类的新实例 |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | 使用 formattedText 对象初始化 {@code TextStamp} 类的新实例 |
| [TextStamp](#TextStamp-java.lang.String-) | 初始化 {@code TextStamp} 类的新实例。 |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | 初始化 TextStamp 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | 自动调整字体大小精度。默认值：0.1； |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | 如果启用，字体大小将自动调整以适应印章矩形的尺寸：{@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) 和 {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。默认宽度和高度来源于页面矩形。 |
| [getDefaultFont](#getDefaultFont--) | 返回默认字体 |
| [getDefaultFontSize](#getDefaultFontSize--) | 默认字体大小 |
| [getDraw](#getDraw--) | 此属性决定印章在页面上的绘制方式。如果 Draw = true，则印章以图形操作符绘制；如果 draw = false，则印章以文本方式绘制。 |
| [getFontSize](#getFontSize--) | 印章放置后的实际字体大小。（如果启用了 'AutoAdjustFontSizeToFitStampRectangle' 选项，可能会与通过构造函数提供的初始字体大小不同。） |
| [getHeight](#getHeight--) | 页面上印章的期望高度。 |
| [getMaxRowWidth](#getMaxRowWidth--) | WordWrap 选项的最大行高。 |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | 获取或设置模式，以定义在字体不包含所请求字符时的行为。 |
| [getReplacementFont](#getReplacementFont--) | 获取或设置用于替换的字体，如果用户字体不包含所需字符。 |
| [getTextAlignment](#getTextAlignment--) | 印章内部文本的对齐方式。 |
| [getTextState](#getTextState--) | 获取印章的文本属性。详情请参阅 {@code TextState}。 |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | 定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。 |
| [getValue](#getValue--) | 获取用作页面印章的字符串值。 |
| [getWidth](#getWidth--) | 页面上印章的期望宽度。 |
| [getWordWrapMode](#getWordWrapMode--) | 获取或设置文本渲染的自动换行模式。 |
| [isJustify](#isJustify--) | 定义文本对齐方式。如果此属性设置为 true，文本的左、右边缘将对齐。默认值：false。 |
| [isScale](#isScale--) | 定义文本的缩放。如果此属性设置为 true 并且指定了 Width 值，文本将被缩放以适应指定的宽度。 |
| [isWordWrap](#isWordWrap--) | 定义自动换行。如果此属性设置为 true 并且指定了 Width 值，文本将被分成多行以适应指定的宽度。默认值：false。 |
| [put](#put-com.aspose.pdf.Page-) | 在页面上添加文本印章。 |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | 自动调整字体大小精度。默认值：0.1； |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | 如果启用，字体大小将自动调整以适应印章矩形的尺寸：{@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) 和 {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。默认宽度和高度来源于页面矩形。 |
| [setDraw](#setDraw-boolean-) | 此属性决定印章在页面上的绘制方式。如果 Draw = true，则印章以图形操作符绘制；如果 draw = false，则印章以文本方式绘制。 |
| [setHeight](#setHeight-double-) | 页面上印章的期望高度。 |
| [setJustify](#setJustify-boolean-) | 定义文本对齐方式。如果此属性设置为 true，文本的左、右边缘将对齐。默认值：false。 |
| [setMaxRowWidth](#setMaxRowWidth-double-) | WordWrap 选项的最大行高。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | 获取或设置模式，以定义在字体不包含所请求字符时的行为。 |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | 获取或设置用于替换的字体，如果用户字体不包含所需字符。 |
| [setScale](#setScale-boolean-) | 定义文本的缩放。如果此属性设置为 true 并且指定了 Width 值，文本将被缩放以适应指定的宽度。 |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | 印章内部文本的对齐方式。 |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | 定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。 |
| [setValue](#setValue-java.lang.String-) | 设置用作页面印章的字符串值。 |
| [setWidth](#setWidth-double-) | 页面上印章的期望宽度。 |
| [setWordWrap](#setWordWrap-boolean-) | 定义自动换行。如果此属性设置为 true 并且指定了 Width 值，文本将被分成多行以适应指定的宽度。默认值：false。 |
| [setWordWrapMode](#setWordWrapMode-int-) | 获取或设置文本渲染的自动换行模式。 |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
使用 formattedText 对象初始化 {@code TextStamp} 类的新实例

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
使用 formattedText 对象初始化 {@code TextStamp} 类的新实例

### TextStamp {#TextStamp-java.lang.String-}
初始化 {@code TextStamp} 类的新实例。

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
初始化 TextStamp 类的新实例。

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

自动调整字体大小精度。默认值：0.1；

**Returns:**
float 值

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

如果启用，字体大小将自动调整以适应印章矩形的尺寸：{@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) 和 {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。默认宽度和高度来源于页面矩形。

**Returns:**
布尔值

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

返回默认字体

**Returns:**
com.aspose.pdf.Font 对象

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

默认字体大小

**Returns:**
float 值

### getDraw {#getDraw--}
```
public boolean getDraw()
```

此属性决定印章在页面上的绘制方式。如果 Draw = true，则印章以图形操作符绘制；如果 draw = false，则印章以文本方式绘制。

**Returns:**
布尔值

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

印章放置后的实际字体大小。（如果启用了 'AutoAdjustFontSizeToFitStampRectangle' 选项，可能会与通过构造函数提供的初始字体大小不同。）

**Returns:**
float 值

### getHeight {#getHeight--}
```
public double getHeight()
```

页面上印章的期望高度。

**Returns:**
double 值

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

WordWrap 选项的最大行高。

**Returns:**
double 值

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

获取或设置模式，以定义在字体不包含所请求字符时的行为。

**Returns:**
NoCharacterAction 元素

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

获取或设置用于替换的字体，如果用户字体不包含所需字符。

**Returns:**
字体实例

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

印章内部文本的对齐方式。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

获取印章的文本属性。详情请参阅 {@code TextState}。

**Returns:**
TextState 元素

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。

**Returns:**
布尔值

### getValue {#getValue--}
```
public String getValue()
```

获取用作页面印章的字符串值。

**Returns:**
字符串值

### getWidth {#getWidth--}
```
public double getWidth()
```

页面上印章的期望宽度。

**Returns:**
double 值

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

获取或设置文本渲染的自动换行模式。

**Returns:**
WordWrapMode 元素

### isJustify {#isJustify--}
```
public boolean isJustify()
```

定义文本对齐方式。如果此属性设置为 true，文本的左、右边缘将对齐。默认值：false。

**Returns:**
布尔值

### isScale {#isScale--}
```
public boolean isScale()
```

定义文本的缩放。如果此属性设置为 true 并且指定了 Width 值，文本将被缩放以适应指定的宽度。

**Returns:**
布尔值

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

定义自动换行。如果此属性设置为 true 并且指定了 Width 值，文本将被分成多行以适应指定的宽度。默认值：false。

**Returns:**
布尔值 @deprecated "Use WordWrapMode instead."

### put {#put-com.aspose.pdf.Page-}
在页面上添加文本印章。

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

自动调整字体大小精度。默认值：0.1；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

如果启用，字体大小将自动调整以适应印章矩形的尺寸：{@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) 和 {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)})。默认宽度和高度来源于页面矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

此属性决定印章在页面上的绘制方式。如果 Draw = true，则印章以图形操作符绘制；如果 draw = false，则印章以文本方式绘制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

页面上印章的期望高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

定义文本对齐方式。如果此属性设置为 true，文本的左、右边缘将对齐。默认值：false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

WordWrap 选项的最大行高。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

获取或设置模式，以定义在字体不包含所请求字符时的行为。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | NoCharacterAction 元素 |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
获取或设置用于替换的字体，如果用户字体不包含所需字符。

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

定义文本的缩放。如果此属性设置为 true 并且指定了 Width 值，文本将被缩放以适应指定的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
印章内部文本的对齐方式。

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setValue {#setValue-java.lang.String-}
设置用作页面印章的字符串值。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

页面上印章的期望宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

定义自动换行。如果此属性设置为 true 并且指定了 Width 值，文本将被分成多行以适应指定的宽度。默认值：false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 @deprecated "Use WordWrapMode instead." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

获取或设置文本渲染的自动换行模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | WordWrapMode 元素 @see WordWrapMode |
