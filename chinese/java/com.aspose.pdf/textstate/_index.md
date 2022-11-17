---
title: TextState
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本的文本状态
type: docs
weight: 389
url: /zh/java/com.aspose.pdf/textstate/
---
**遗产：**
java.lang.Object
```
public class TextState
```

表示文本的文本状态
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextState()](#TextState--) | 创建文本状态对象。 |
| [TextState(double fontSize)](#TextState-double-) | 创建具有字体大小规范的文本状态对象。 |
| [TextState(Color foregroundColor)](#TextState-java.awt.Color-) | 创建具有前景色规范的文本状态对象。 |
| [TextState(Color foregroundColor, double fontSize)](#TextState-java.awt.Color-double-) | 创建具有前景色和字体大小规范的文本状态对象。 |
| [TextState(String fontFamily)](#TextState-java.lang.String-) | 创建具有字体系列规范的文本状态对象。 |
| [TextState(String fontFamily, boolean bold, boolean italic)](#TextState-java.lang.String-boolean-boolean-) | 使用字体系列和字体样式规范创建文本状态对象。 |
| [TextState(String fontFamily, double fontSize)](#TextState-java.lang.String-double-) | 创建具有字体系列和字体大小规范的文本状态对象。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [TabTag](#TabTag) | 您可以将此标记放在文本中以声明列表。 |
| [TabstopDefaultValue](#TabstopDefaultValue) | 默认字体空格字符宽度列表的默认值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | 应用来自另一个 textState 的设置 |
| [calculateFontSize(String str, Rectangle rect)](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | 计算矩形的字体大小。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取文本的背景颜色。 |
| [getCharacterSpacing()](#getCharacterSpacing--) | 获取文本的字符间距。 |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | 获取文本的字体。 |
| [getFontSize()](#getFontSize--) | 获取文本的字体大小。 |
| [getFontStyle()](#getFontStyle--) | 设置文本的字体样式。 |
| [getForegroundColor()](#getForegroundColor--) | 获取文本的前景色。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取文本的水平对齐方式。 |
| [getHorizontalScaling()](#getHorizontalScaling--) | 获取文本的水平缩放比例。 |
| [getLineSpacing()](#getLineSpacing--) | 获取文本的行间距。 |
| [getRenderingMode()](#getRenderingMode--) | 获取或设置文本的渲染模式。 |
| [getStrikeOut()](#getStrikeOut--) | 获取文本的删除线，由 TextFragment 对象表示 |
| [getStrokingColor()](#getStrokingColor--) | 获取或设置文本的前景色。 |
| [getTextHeight()](#getTextHeight--) | 获取文字高度。 |
| [getWordSpacing()](#getWordSpacing--) | 获取文本的字间距。 |
| [hashCode()](#hashCode--) |  |
| [isInvisible()](#isInvisible--) | 获取或设置文本的不可见性。 |
| [isSubscript()](#isSubscript--) | 获取或设置文本的下标。 |
| [isSuperscript()](#isSuperscript--) | 获取文本的上标。 |
| [isUnderline()](#isUnderline--) | 获取文本的下划线，由 TextFragment 对象表示 |
| [measureString(String str)](#measureString-java.lang.String-) | 测量字符串。 |
| [measureString(String str, boolean insideLine)](#measureString-java.lang.String-boolean-) | 测量字符串。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本的背景颜色。 |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | 设置文本的字符间距。 |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | 获取文本的字体。 |
| [setFontSize(float value)](#setFontSize-float-) | 设置文本的字体大小。 |
| [setFontSizeSuppressedUpdate(float value)](#setFontSizeSuppressedUpdate-float-) | 设置希望抑制更新的文本的字体大小。 |
| [setFontStyle(int value)](#setFontStyle-int-) | 设置文本的字体样式。 |
| [setFontSuppressedUpdate(Font value)](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | 获取希望抑制更新的文本字体。 |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | 设置文本的前景色。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置文本的水平对齐方式。 |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | 设置文本的水平缩放。 |
| [setInvisible(boolean value)](#setInvisible-boolean-) | 获取或设置文本的不可见性。 |
| [setLineSpacing(float value)](#setLineSpacing-float-) | 设置文本的行间距。 |
| [setRenderingMode(int value)](#setRenderingMode-int-) | 获取或设置文本的渲染模式。 |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | 为文本设置删除线，由 TextFragment 对象表示 |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | 获取或设置文本的前景色。 |
| [setSubscript(boolean value)](#setSubscript-boolean-) | 获取或设置文本的下标。 |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | 设置文本的上标。 |
| [setUnderline(boolean value)](#setUnderline-boolean-) | 为文本设置下划线，由 TextFragment 对象表示 |
| [setWordSpacing(float value)](#setWordSpacing-float-) | 设置文本的字间距。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextState() {#TextState--}
```
public TextState()
```


创建文本状态对象。

### TextState(double fontSize) {#TextState-double-}
```
public TextState(double fontSize)
```


创建具有字体大小规范的文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontSize | double | 字体大小。 |

### TextState(Color foregroundColor) {#TextState-java.awt.Color-}
```
public TextState(Color foregroundColor)
```


创建具有前景色规范的文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| foregroundColor | java.awt.Color | 前景色。 |

### TextState(Color foregroundColor, double fontSize) {#TextState-java.awt.Color-double-}
```
public TextState(Color foregroundColor, double fontSize)
```


创建具有前景色和字体大小规范的文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| foregroundColor | java.awt.Color | 前景色。 |
| fontSize | double | 字体大小。 |

### TextState(String fontFamily) {#TextState-java.lang.String-}
```
public TextState(String fontFamily)
```


创建具有字体系列规范的文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFamily | java.lang.String | 字体系列。 |

### TextState(String fontFamily, boolean bold, boolean italic) {#TextState-java.lang.String-boolean-boolean-}
```
public TextState(String fontFamily, boolean bold, boolean italic)
```


使用字体系列和字体样式规范创建文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFamily | java.lang.String | 字体系列。 |
| bold | boolean | 粗体字体样式。 |
| italic | boolean | 斜体字体样式。 |

### TextState(String fontFamily, double fontSize) {#TextState-java.lang.String-double-}
```
public TextState(String fontFamily, double fontSize)
```


创建具有字体系列和字体大小规范的文本状态对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFamily | java.lang.String | 字体系列。 |
| fontSize | double | 字体大小。 |

### TabTag {#TabTag}
```
public static final String TabTag
```


您可以将此标记放在文本中以声明列表。

--------------------

它仅在与 TabStops 结合时有效。

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```


默认字体空格字符宽度列表的默认值。

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


应用来自另一个 textState 的设置

--------------------

只有那些明确更改的属性才会被复制。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象。 |

### calculateFontSize(String str, Rectangle rect) {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
```
public double calculateFontSize(String str, Rectangle rect)
```


计算矩形的字体大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串值 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

**退货：**
双倍价值
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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取文本的背景颜色。

--------------------

请注意，该值不会保留为文档中的文本特征。 BackgroundColor 属性 getter 适用于一个对象，以防先前使用 BackgroundColor setter 为这些对象显式设置它。该属性由运行时在当前生成/修改过程的上下文中使用。

**退货：**
[Color](../../com.aspose.pdf/color) - 颜色值
### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


获取文本的字符间距。

**退货：**
float - 浮点值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFont() {#getFont--}
```
public Font getFont()
```


获取文本的字体。

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


获取文本的字体大小。

**退货：**
float - 浮点值
### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


设置文本的字体样式。

**退货：**
int - 字体样式元素
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


获取文本的前景色。

**退货：**
[Color](../../com.aspose.pdf/color) - 颜色值
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取文本的水平对齐方式。

--------------------

HorizontalAlignment.None 等于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅适用于新文档生成方案。

**退货：**
int - HorizontalAlignment 值
### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


获取文本的水平缩放比例。

**退货：**
float - 浮点值
### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


获取文本的行间距。

**退货：**
float - 浮点值

--------------------

请注意，该值不会保留为文档中的文本特征。 LineSpacing 属性 getter 适用于一个对象，以防先前使用 LineSpacing setter 为这些对象显式设置它。该属性由运行时在当前生成/修改过程的上下文中使用。
### getRenderingMode() {#getRenderingMode--}
```
public int getRenderingMode()
```


获取或设置文本的渲染模式。

**退货：**
int - TextRenderingMode 元素
### getStrikeOut() {#getStrikeOut--}
```
public boolean getStrikeOut()
```


获取文本的删除线，由 TextFragment 对象表示

**退货：**
boolean - 布尔值
### getStrokingColor() {#getStrokingColor--}
```
public Color getStrokingColor()
```


获取或设置文本的前景色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


获取文字高度。

**退货：**
float - 浮点值
### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```


获取文本的字间距。

**退货：**
float - 浮点值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isInvisible() {#isInvisible--}
```
public boolean isInvisible()
```


获取或设置文本的不可见性。这基本上反映了 RenderingMode (\#getRenderingMode.getRenderingMode/\#setRenderingMode(int).setRenderingMode(int)) 状态，一些特殊情况除外（如裁剪）。

**退货：**
boolean - 布尔值
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


获取或设置文本的下标。

**退货：**
boolean - 布尔值
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


获取文本的上标。

**退货：**
boolean - 布尔值
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


获取文本的下划线，由 TextFragment 对象表示

**退货：**
boolean - 布尔值
### measureString(String str) {#measureString-java.lang.String-}
```
public double measureString(String str)
```


测量字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串。 |

**退货：**
double - 用此文本状态表示的字符串的宽度。
### measureString(String str, boolean insideLine) {#measureString-java.lang.String-boolean-}
```
public double measureString(String str, boolean insideLine)
```


测量字符串。

--------------------

insideLine 表示字符串没有结束。如果测量了整个字符串的一部分 - insideLine 应该为真。如果测量整个字符串，则 insideLine 应该为 false。换句话说：在 insideLine = true 的情况下，只考虑字符宽度。如果 insideLine = false 正确处理了字符串的结尾，则不会考虑其他转换 - 会考虑斜体转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串值 |
| insideLine | boolean | 布尔值 |

**退货：**
双倍价值
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


设置文本的背景颜色。

--------------------

请注意，该值不会保留为文档中的文本特征。 BackgroundColor 属性 getter 适用于一个对象，以防先前使用 BackgroundColor setter 为这些对象显式设置它。该属性由运行时在当前生成/修改过程的上下文中使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 色值 |

### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```


设置文本的字符间距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


获取文本的字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体对象 |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


设置文本的字体大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setFontSizeSuppressedUpdate(float value) {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```


设置希望抑制更新的文本的字体大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


设置文本的字体样式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 字体样式值 |

### setFontSuppressedUpdate(Font value) {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
```
public void setFontSuppressedUpdate(Font value)
```


获取希望抑制更新的文本字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体对象 |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public void setForegroundColor(Color value)
```


设置文本的前景色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 色值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置文本的水平对齐方式。

--------------------

HorizontalAlignment.None 等于 HorizontalAlignment.Left。请注意，TextState.HorizontalAlignment 属性仅适用于新文档生成方案。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


设置文本的水平缩放。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


获取或设置文本的不可见性。这基本上反映了 RenderingMode (\#getRenderingMode.getRenderingMode/\#setRenderingMode(int).setRenderingMode(int)) 状态，一些特殊情况除外（如裁剪）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```


设置文本的行间距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值

--------------------

请注意，该值不会保留为文档中的文本特征。 LineSpacing 属性 getter 适用于一个对象，以防先前使用 LineSpacing setter 为这些对象显式设置它。该属性由运行时在当前生成/修改过程的上下文中使用。|

### setRenderingMode(int value) {#setRenderingMode-int-}
```
public void setRenderingMode(int value)
```


获取或设置文本的渲染模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | TextRenderingMode 元素 |

### setStrikeOut(boolean value) {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```


为文本设置删除线，由 TextFragment 对象表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setStrokingColor(Color value) {#setStrokingColor-com.aspose.pdf.Color-}
```
public void setStrokingColor(Color value)
```


获取或设置文本的前景色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


获取或设置文本的下标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


设置文本的上标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```


为文本设置下划线，由 TextFragment 对象表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```


设置文本的字间距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

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
