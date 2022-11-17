---
title: StructureTextState
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Text Structure Elements 和 TaggedContent ITextElement ITaggedContent 的文本状态设置
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**遗产：**
java.lang.Object
```
public class StructureTextState
```

表示 Text Structure Elements 和 TaggedContent (ITextElement, ITaggedContent) 的文本状态设置
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructureTextState()](#StructureTextState--) | 默认构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createTextState()](#createTextState--) | 创建文本状态 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置文本的背景颜色。 |
| [getCharacterSpacing()](#getCharacterSpacing--) | 获取或设置文本的字符间距。 |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | 获取或设置文本的字体。 |
| [getFontSize()](#getFontSize--) | 获取或设置文本的字体大小。 |
| [getFontStyle()](#getFontStyle--) | 获取或设置文本的字体样式。 |
| [getForegroundColor()](#getForegroundColor--) | 获取或设置文本的前景色。 |
| [getHorizontalScaling()](#getHorizontalScaling--) | 获取或设置文本的水平缩放比例。 |
| [getLineSpacing()](#getLineSpacing--) | 获取或设置文本的行间距。 |
| [getMarginInfo()](#getMarginInfo--) | 获取或设置块结构元素的边距。 |
| [getStrikeOut()](#getStrikeOut--) | 获取或设置文本的删除线。 |
| [getSubscript()](#getSubscript--) | 获取或设置文本的下标。 |
| [getSuperscript()](#getSuperscript--) | 获取或设置文本的上标。 |
| [getUnderline()](#getUnderline--) | 获取或设置文本的下划线。 |
| [getWordSpacing()](#getWordSpacing--) | 获取或设置文本的字间距。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置文本的背景颜色。 |
| [setCharacterSpacing(Float value)](#setCharacterSpacing-java.lang.Float-) | 获取或设置文本的字符间距。 |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | 获取或设置文本的字体。 |
| [setFontSize(Float value)](#setFontSize-java.lang.Float-) | 获取或设置文本的字体大小。 |
| [setFontStyle(Integer value)](#setFontStyle-java.lang.Integer-) | 获取或设置文本的字体样式。 |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | 获取或设置文本的前景色。 |
| [setHorizontalScaling(Float value)](#setHorizontalScaling-java.lang.Float-) | 获取或设置文本的水平缩放比例。 |
| [setLineSpacing(Float value)](#setLineSpacing-java.lang.Float-) | 获取或设置文本的行间距。 |
| [setMarginInfo(MarginInfo value)](#setMarginInfo-com.aspose.pdf.MarginInfo-) | 获取或设置块结构元素的边距。 |
| [setStrikeOut(Boolean value)](#setStrikeOut-java.lang.Boolean-) | 获取或设置文本的删除线。 |
| [setSubscript(Boolean value)](#setSubscript-java.lang.Boolean-) | 获取或设置文本的下标。 |
| [setSuperscript(Boolean value)](#setSuperscript-java.lang.Boolean-) | 获取或设置文本的上标。 |
| [setUnderline(Boolean value)](#setUnderline-java.lang.Boolean-) | 获取或设置文本的下划线。 |
| [setWordSpacing(Float value)](#setWordSpacing-java.lang.Float-) | 获取或设置文本的字间距。 |
| [toString()](#toString--) |  |
| [update(StructureTextState structureTextState)](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | 更新元素 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureTextState() {#StructureTextState--}
```
public StructureTextState()
```


默认构造函数

### createTextState() {#createTextState--}
```
public final TextState createTextState()
```


创建文本状态

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
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
public final Color getBackgroundColor()
```


获取或设置文本的背景颜色。

可以为空。使用 null 从父结构元素继承 BackgroundColor 属性。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getCharacterSpacing() {#getCharacterSpacing--}
```
public final Float[] getCharacterSpacing()
```


获取或设置文本的字符间距。

可以为空。使用 null 从父结构元素继承 CharacterSpacing 属性。

**退货：**
java.lang.Float[- 浮动数组
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFont() {#getFont--}
```
public final Font getFont()
```


获取或设置文本的字体。

可以为空。使用 null 从父结构元素继承 Font 属性。

**退货：**
[Font](../../com.aspose.pdf/font) 字体实例
### getFontSize() {#getFontSize--}
```
public final Float[] getFontSize()
```


获取或设置文本的字体大小。

可以为空。使用 null 从父结构元素继承 FontSize 属性。

**退货：**
java.lang.Float[- 浮动数组
### getFontStyle() {#getFontStyle--}
```
public final Integer[] getFontStyle()
```


获取或设置文本的字体样式。

可以为空。使用 null 从父结构元素继承 FontStyle 属性。

**退货：**
java.lang.整数[- 整数数组
### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


获取或设置文本的前景色。

可以为空。使用 null 从父结构元素继承 ForegroundColor 属性。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色实例
### getHorizontalScaling() {#getHorizontalScaling--}
```
public final Float[] getHorizontalScaling()
```


获取或设置文本的水平缩放比例。

可以为空。使用 null 从父结构元素继承 HorizontalScaling 属性。

**退货：**
java.lang.Float[- 浮动数组
### getLineSpacing() {#getLineSpacing--}
```
public final Float[] getLineSpacing()
```


获取或设置文本的行间距。

可以为空。使用 null 从父结构元素继承 LineSpacing 属性。

**退货：**
java.lang.Float[- 浮动数组
### getMarginInfo() {#getMarginInfo--}
```
public final MarginInfo getMarginInfo()
```


获取或设置块结构元素的边距。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getStrikeOut() {#getStrikeOut--}
```
public final Boolean[] getStrikeOut()
```


获取或设置文本的删除线。

可以为空。使用 null 从父结构元素继承 StrikeOut 属性。

**退货：**
java.lang.布尔值[- 布尔数组
### getSubscript() {#getSubscript--}
```
public final Boolean[] getSubscript()
```


获取或设置文本的下标。

可以为空。使用 null 从父结构元素继承 Subscript 属性。

**退货：**
java.lang.布尔值[- 布尔数组
### getSuperscript() {#getSuperscript--}
```
public final Boolean[] getSuperscript()
```


获取或设置文本的上标。

可以为空。使用 null 从父结构元素继承 Superscript 属性。

**退货：**
java.lang.布尔值[- 布尔数组
### getUnderline() {#getUnderline--}
```
public final Boolean[] getUnderline()
```


获取或设置文本的下划线。

可以为空。使用 null 从父结构元素继承 Underline 属性。

**退货：**
java.lang.布尔值[- 布尔数组
### getWordSpacing() {#getWordSpacing--}
```
public final Float[] getWordSpacing()
```


获取或设置文本的字间距。

可以为空。使用 null 从父结构元素继承 WordSpacing 属性。

**退货：**
java.lang.Float[- 浮动数组
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


获取或设置文本的背景颜色。

可以为空。使用 null 从父结构元素继承 BackgroundColor 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setCharacterSpacing(Float value) {#setCharacterSpacing-java.lang.Float-}
```
public final void setCharacterSpacing(Float value)
```


获取或设置文本的字符间距。

可以为空。使用 null 从父结构元素继承 CharacterSpacing 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Float | 浮动值 |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public final void setFont(Font value)
```


获取或设置文本的字体。

可以为空。使用 null 从父结构元素继承 Font 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | 字体实例 |

### setFontSize(Float value) {#setFontSize-java.lang.Float-}
```
public final void setFontSize(Float value)
```


获取或设置文本的字体大小。

可以为空。使用 null 从父结构元素继承 FontSize 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Float | 浮动值 |

### setFontStyle(Integer value) {#setFontStyle-java.lang.Integer-}
```
public final void setFontStyle(Integer value)
```


获取或设置文本的字体样式。

可以为空。使用 null 从父结构元素继承 FontStyle 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Integer | FontStyle 元素值 |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public final void setForegroundColor(Color value)
```


获取或设置文本的前景色。

可以为空。使用 null 从父结构元素继承 ForegroundColor 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色实例 |

### setHorizontalScaling(Float value) {#setHorizontalScaling-java.lang.Float-}
```
public final void setHorizontalScaling(Float value)
```


获取或设置文本的水平缩放比例。

可以为空。使用 null 从父结构元素继承 HorizontalScaling 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Float | 浮动值 |

### setLineSpacing(Float value) {#setLineSpacing-java.lang.Float-}
```
public final void setLineSpacing(Float value)
```


获取或设置文本的行间距。

可以为空。使用 null 从父结构元素继承 LineSpacing 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Float | 浮动值 |

### setMarginInfo(MarginInfo value) {#setMarginInfo-com.aspose.pdf.MarginInfo-}
```
public final void setMarginInfo(MarginInfo value)
```


获取或设置块结构元素的边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setStrikeOut(Boolean value) {#setStrikeOut-java.lang.Boolean-}
```
public final void setStrikeOut(Boolean value)
```


获取或设置文本的删除线。

可以为空。使用 null 从父结构元素继承 StrikeOut 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Boolean | 布尔值 |

### setSubscript(Boolean value) {#setSubscript-java.lang.Boolean-}
```
public final void setSubscript(Boolean value)
```


获取或设置文本的下标。

可以为空。使用 null 从父结构元素继承 Subscript 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Boolean | 布尔值 |

### setSuperscript(Boolean value) {#setSuperscript-java.lang.Boolean-}
```
public final void setSuperscript(Boolean value)
```


获取或设置文本的上标。

可以为空。使用 null 从父结构元素继承 Superscript 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Boolean | 布尔值 |

### setUnderline(Boolean value) {#setUnderline-java.lang.Boolean-}
```
public final void setUnderline(Boolean value)
```


获取或设置文本的下划线。

可以为空。使用 null 从父结构元素继承 Underline 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Boolean | 布尔值 |

### setWordSpacing(Float value) {#setWordSpacing-java.lang.Float-}
```
public final void setWordSpacing(Float value)
```


获取或设置文本的字间距。

可以为空。使用 null 从父结构元素继承 WordSpacing 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Float | 浮动值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### update(StructureTextState structureTextState) {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
```
public final void update(StructureTextState structureTextState)
```


更新元素

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| structureTextState | [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) | StructureTextState 实例 |

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
