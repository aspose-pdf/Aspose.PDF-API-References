---
title: TextFragmentState
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本片段的文本状态。
type: docs
weight: 375
url: /zh/java/com.aspose.pdf/textfragmentstate/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextState](../../com.aspose.pdf/textstate)
```
public final class TextFragmentState extends TextState
```

表示文本片段的文本状态。

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object.
 
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);
  
  //更改第一个文本出现的前景色
  absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
  //更改第一个文本出现的字体大小
  absorber.getTextFragments().get(1).getTextState().setFontSize ( 15);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

提供更改文本以下属性的方法：字体（TextFragmentState.Font 属性）字体大小（TextFragmentState.FontSize 属性）字体样式（TextFragmentState.FontStyle 属性）前景颜色（TextFragmentState.ForegroundColor 属性）背景颜色（TextFragmentState.BackgroundColor 属性）请注意，更改 TextFragmentState 属性可能会更改内部 TextFragment.Segments 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的要求是保持 TextFragment.Segments 集合不变，请单独更改内部段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragmentState(TextFragment fragment)](#TextFragmentState-com.aspose.pdf.TextFragment-) | 使用指定的 TextFragment 对象初始化 TextFragmentState 对象的新实例。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [TabTag](#TabTag) | 您可以将此标记放在文本中以声明列表。 |
| [TabstopDefaultValue](#TabstopDefaultValue) | 默认字体空格字符宽度列表的默认值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | 应用来自另一个 textState 的设置 |
| [applyChangesFrom(TextState textState, boolean groupChangesOnly)](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | 应用来自另一个 textState 的设置 |
| [calculateFontSize(String str, Rectangle rect)](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | 计算矩形的字体大小。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 设置文本的背景颜色，由 TextFragment 对象表示 |
| [getCharacterSpacing()](#getCharacterSpacing--) | 获取文本的字符间距，由 TextFragment 对象表示。 |
| [getClass()](#getClass--) |  |
| [getDrawTextRectangleBorder()](#getDrawTextRectangleBorder--) | 获取是否绘制文本矩形边框的标志。 |
| [getFont()](#getFont--) | 获取文本的字体，由 TextFragment 对象表示 |
| [getFontSize()](#getFontSize--) | 获取文本的字体大小，由 TextFragment 对象表示 |
| [getFontStyle()](#getFontStyle--) | 设置文本的字体样式，由 TextFragment 对象表示 |
| [getForegroundColor()](#getForegroundColor--) | 获取文本的前景色，由 TextFragment 对象表示 |
| [getFormattingOptions()](#getFormattingOptions--) | 获取或设置格式化选项。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取文本的水平对齐方式。 |
| [getHorizontalScaling()](#getHorizontalScaling--) | 获取由 TextFragment 对象表示的文本的水平缩放。 |
| [getLineSpacing()](#getLineSpacing--) | 获取文本的行间距。 |
| [getRenderingMode()](#getRenderingMode--) | 获取或设置文本的渲染模式。 |
| [getRotation()](#getRotation--) | 获取或设置以度为单位的旋转角度。 |
| [getStrikeOut()](#getStrikeOut--) | 获取文本的删除线，由 TextFragment 对象表示 |
| [getStrokingColor()](#getStrokingColor--) | 获取或设置TextFragment渲染的颜色描边操作（描边文字、矩形边框） |
| [getTabStops()](#getTabStops--) | 获取文本的制表位。 |
| [getTextHeight()](#getTextHeight--) | 获取文本高度，由 TextFragment 对象表示 |
| [getUnderline()](#getUnderline--) | 获取或设置文本的下划线，由[TextFragment](../../com.aspose.pdf/textfragment)目的 |
| [getWordSpacing()](#getWordSpacing--) | 获取文本的字间距。 |
| [hashCode()](#hashCode--) |  |
| [isInvisible()](#isInvisible--) | 获取文本的不可见性。 |
| [isSubscript()](#isSubscript--) | 获取或设置文本的下标，由 TextFragment 对象表示。 |
| [isSuperscript()](#isSuperscript--) | 获取或设置文本的上标，由 TextFragment 对象表示。 |
| [isUnderline()](#isUnderline--) | 获取文本的下划线，由 TextFragment 对象表示 |
| [measureString(String str)](#measureString-java.lang.String-) | 测量字符串。 |
| [measureString(String str, boolean insideLine)](#measureString-java.lang.String-boolean-) | 测量字符串。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置文本的背景颜色，由[TextFragment](../../com.aspose.pdf/textfragment)目的 |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | 设置文本的字符间距，由 TextFragment 对象表示。 |
| [setDrawTextRectangleBorder(boolean value)](#setDrawTextRectangleBorder-boolean-) | 设置文本矩形边框是否绘制标志。 |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | 设置文本的字体，由 TextFragment 对象表示 |
| [setFontSize(float value)](#setFontSize-float-) | 设置文本的字体大小，由 TextFragment 对象表示 |
| [setFontSizeSuppressedUpdate(float value)](#setFontSizeSuppressedUpdate-float-) | 设置希望抑制更新的文本的字体大小。 |
| [setFontStyle(int value)](#setFontStyle-int-) | 设置文本的字体样式，由[TextFragment](../../com.aspose.pdf/textfragment)目的 |
| [setFontSuppressedUpdate(Font value)](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | 获取希望抑制更新的文本字体。 |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | 设置文本的前景色，由 TextFragment 对象表示 |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | 获取或设置格式化选项。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置文本的水平对齐方式。 |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | 设置文本的水平缩放，由 TextFragment 对象表示。 |
| [setInvisible(boolean value)](#setInvisible-boolean-) | 设置文本的不可见性。 |
| [setLineSpacing(float value)](#setLineSpacing-float-) | 设置文本的行间距。 |
| [setRenderingMode(int value)](#setRenderingMode-int-) | 获取或设置文本的渲染模式。 |
| [setRotation(double value)](#setRotation-double-) | 获取或设置以度为单位的旋转角度。 |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | 为文本设置删除线，由 TextFragment 对象表示 |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | 获取或设置TextFragment渲染的颜色描边操作（描边文字、矩形边框） |
| [setSubscript(boolean value)](#setSubscript-boolean-) | 获取或设置文本的下标，由 TextFragment 对象表示。 |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | 获取或设置文本的上标，由 TextFragment 对象表示。 |
| [setUnderline(boolean value)](#setUnderline-boolean-) | 为文本设置下划线，由 TextFragment 对象表示 |
| [setWordSpacing(float value)](#setWordSpacing-float-) | 设置文本的字间距。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragmentState(TextFragment fragment) {#TextFragmentState-com.aspose.pdf.TextFragment-}
```
public TextFragmentState(TextFragment fragment)
```


使用指定的 TextFragment 对象初始化 TextFragmentState 对象的新实例。不支持此 TextFragmentState 初始化。 TextFragmentState 仅适用于 TextFragment.TextState 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | 文本片段对象。 |

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

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象。

--------------------

只有那些明确更改的属性才会被复制。|

### applyChangesFrom(TextState textState, boolean groupChangesOnly) {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
```
public void applyChangesFrom(TextState textState, boolean groupChangesOnly)
```


应用来自另一个 textState 的设置

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象。 |
| groupChangesOnly | boolean | 如果 true 仅继承组更改（不将段隔离为单个段） |

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


设置文本的背景颜色，由 TextFragment 对象表示

**退货：**
[Color](../../com.aspose.pdf/color) - 值颜色对象
### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


获取文本的字符间距，由 TextFragment 对象表示。

**退货：**
float - 浮点值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDrawTextRectangleBorder() {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```


获取是否绘制文本矩形边框的标志。

**退货：**
boolean - 布尔值
### getFont() {#getFont--}
```
public Font getFont()
```


获取文本的字体，由 TextFragment 对象表示

**退货：**
[Font](../../com.aspose.pdf/font) - 字体值
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


获取文本的字体大小，由 TextFragment 对象表示

**退货：**
float - 浮点值
### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


设置文本的字体样式，由 TextFragment 对象表示

**退货：**
int - 字体样式元素
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


获取文本的前景色，由 TextFragment 对象表示

**退货：**
[Color](../../com.aspose.pdf/color) 颜色对象
### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


获取或设置格式化选项。选项的设置仅在生成器场景中有效。

**退货：**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - TextFormattingOptions 实例
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取文本的水平对齐方式。

--------------------

HorizontalAlignment.None 等于 HorizontalAlignment.Left。请注意，TextFragmentState.VerticalAlignment 属性仅适用于新文档生成方案。

**退货：**
int - HorizontalAlignment 值
### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


获取由 TextFragment 对象表示的文本的水平缩放。

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
整数
### getRotation() {#getRotation--}
```
public double getRotation()
```


获取或设置以度为单位的旋转角度。

**退货：**
双倍价值
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


获取或设置TextFragment渲染的颜色描边操作（描边文字、矩形边框）

**退货：**
[Color](../../com.aspose.pdf/color)
### getTabStops() {#getTabStops--}
```
public TabStops getTabStops()
```


获取文本的制表位。

--------------------

请注意，Tabstops 属性仅适用于新文档生成方案。 Tabstops 可以在 TextFragment 初始化期间添加。必须在文本之前构建制表位。

**退货：**
[TabStops](../../com.aspose.pdf/tabstops) - TabStops 对象
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


获取文本高度，由 TextFragment 对象表示

**退货：**
float - 浮点值
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


获取或设置文本的下划线，由[TextFragment](../../com.aspose.pdf/textfragment)目的

**退货：**
boolean - 布尔值
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


获取文本的不可见性。

**退货：**
boolean - 布尔值
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


获取或设置文本的下标，由 TextFragment 对象表示。

**退货：**
boolean - 布尔值
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


获取或设置文本的上标，由 TextFragment 对象表示。

**退货：**
boolean - value 布尔值
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
double - 双精度值，字符串的宽度。
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


设置文本的背景颜色，由[TextFragment](../../com.aspose.pdf/textfragment)目的

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```


设置文本的字符间距，由 TextFragment 对象表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setDrawTextRectangleBorder(boolean value) {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```


设置文本矩形边框是否绘制标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


设置文本的字体，由 TextFragment 对象表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体值 |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


设置文本的字体大小，由 TextFragment 对象表示

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


设置文本的字体样式，由[TextFragment](../../com.aspose.pdf/textfragment)目的

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

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


设置文本的前景色，由 TextFragment 对象表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色对象 |

### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


获取或设置格式化选项。选项的设置仅在生成器场景中有效。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | TextFormattingOptions 实例 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置文本的水平对齐方式。

--------------------

HorizontalAlignment.None 等于 HorizontalAlignment.Left。请注意，TextFragmentState.VerticalAlignment 属性仅适用于新文档生成方案。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


设置文本的水平缩放，由 TextFragment 对象表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


设置文本的不可见性。

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
| value | int |  |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


获取或设置以度为单位的旋转角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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


获取或设置TextFragment渲染的颜色描边操作（描边文字、矩形边框）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


获取或设置文本的下标，由 TextFragment 对象表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


获取或设置文本的上标，由 TextFragment 对象表示。

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
