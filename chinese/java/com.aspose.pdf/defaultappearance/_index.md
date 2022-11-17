---
title: DefaultAppearance
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述字段字体文本大小和颜色的默认外观。
type: docs
weight: 82
url: /zh/java/com.aspose.pdf/defaultappearance/
---
**遗产：**
java.lang.Object
```
public final class DefaultAppearance
```

描述字段的默认外观（字体、文本大小和颜色）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DefaultAppearance()](#DefaultAppearance--) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance(IPdfDictionary engineDict)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [DefaultAppearance(IPdfPrimitive appearance)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [DefaultAppearance(String fontName, double fontSize, Color textColor)](#DefaultAppearance-java.lang.String-double-java.awt.Color-) | DefaultAppearance 的构造函数。 |
| [DefaultAppearance(Font font, double fontSize, Color textColor)](#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-) | DefaultAppearance 的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | 获取指定为文本默认的字体。 |
| [getFontName()](#getFontName--) | 获取默认外观中的字体名称。 |
| [getFontResourceName()](#getFontResourceName--) | 获取默认外观中的字体名称。 |
| [getFontSize()](#getFontSize--) | 获取默认外观的字体大小。 |
| [getText()](#getText--) | 获取表示外观的 pdf 运算符列表。 |
| [getTextColor()](#getTextColor--) | 获取默认外观中文本的颜色。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFontName(String value)](#setFontName-java.lang.String-) | 获取默认外观中的字体名称。 |
| [setFontResourceName(String value)](#setFontResourceName-java.lang.String-) | 获取默认外观中的字体名称。 |
| [setFontSize(double value)](#setFontSize-double-) | 设置默认外观的字体大小。 |
| [setTextColor(Color color)](#setTextColor-java.awt.Color-) | 设置默认外观中的文本颜色。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DefaultAppearance() {#DefaultAppearance--}
```
public DefaultAppearance()
```


DefaultAppearance 的构造函数。

### DefaultAppearance(IPdfDictionary engineDict) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public DefaultAppearance(IPdfDictionary engineDict)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| engineDict | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### DefaultAppearance(IPdfPrimitive appearance) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public DefaultAppearance(IPdfPrimitive appearance)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| appearance | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### DefaultAppearance(String fontName, double fontSize, Color textColor) {#DefaultAppearance-java.lang.String-double-java.awt.Color-}
```
public DefaultAppearance(String fontName, double fontSize, Color textColor)
```


DefaultAppearance 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体名称。 |
| fontSize | double | 字体大小。 |
| textColor | java.awt.Color | 文本的颜色。 |

### DefaultAppearance(Font font, double fontSize, Color textColor) {#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-}
```
public DefaultAppearance(Font font, double fontSize, Color textColor)
```


DefaultAppearance 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | 将用作默认字体。 |
| fontSize | double | 字体大小。 |
| textColor | java.awt.Color | 文本的颜色。 |

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
### getFont() {#getFont--}
```
public Font getFont()
```


获取指定为文本默认的字体。

**退货：**
[Font](../../com.aspose.pdf/font) - 字体值
### getFontName() {#getFontName--}
```
public String getFontName()
```


获取默认外观中的字体名称。

**退货：**
java.lang.String - 字符串值
### getFontResourceName() {#getFontResourceName--}
```
public final String getFontResourceName()
```


获取默认外观中的字体名称。

**退货：**
java.lang.String - 字符串值
### getFontSize() {#getFontSize--}
```
public double getFontSize()
```


获取默认外观的字体大小。

**退货：**
双字号
### getText() {#getText--}
```
public String getText()
```


获取表示外观的 pdf 运算符列表。

**退货：**
java.lang.String - 字符串值
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


获取默认外观中文本的颜色。

**退货：**
[Color](../../java.awt/color) 颜色对象
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




### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


获取默认外观中的字体名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setFontResourceName(String value) {#setFontResourceName-java.lang.String-}
```
public final void setFontResourceName(String value)
```


获取默认外观中的字体名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setFontSize(double value) {#setFontSize-double-}
```
public void setFontSize(double value)
```


设置默认外观的字体大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 字体大小 |

### setTextColor(Color color) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color color)
```


设置默认外观中的文本颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | java.awt.Color | 颜色对象 |

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
