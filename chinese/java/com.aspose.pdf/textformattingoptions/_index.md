---
title: TextFormattingOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本格式选项
type: docs
weight: 371
url: /zh/java/com.aspose.pdf/textformattingoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextFormattingOptions extends TextOptions
```

表示文本格式选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFormattingOptions(int wrapMode)](#TextFormattingOptions-int-) | 为指定的自动换行模式初始化 TextFormattingOptions 对象的新实例。 |
| [TextFormattingOptions()](#TextFormattingOptions--) | 使用未定义的自动换行模式初始化 TextFormattingOptions 对象的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstLineIndent()](#getFirstLineIndent--) | 获取或设置首行缩进值。 |
| [getHyphenSymbol()](#getHyphenSymbol--) | 获取或设置在断字过程中使用的连字符。 |
| [getLineSpacing()](#getLineSpacing--) | 获取行距模式。 |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | 获取或设置后续行缩进值。 |
| [getWrapMode()](#getWrapMode--) | 获取自动换行模式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | 获取或设置首行缩进值。 |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | 获取或设置在断字过程中使用的连字符。 |
| [setLineSpacing(int value)](#setLineSpacing-int-) | 设置行距模式。 |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | 获取或设置后续行缩进值。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 设置自动换行模式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFormattingOptions(int wrapMode) {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```


为指定的自动换行模式初始化 TextFormattingOptions 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| wrapMode | int | 自动换行模式。 |

### TextFormattingOptions() {#TextFormattingOptions--}
```
public TextFormattingOptions()
```


使用未定义的自动换行模式初始化 TextFormattingOptions 对象的新实例。

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
### getFirstLineIndent() {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```


获取或设置首行缩进值。

**退货：**
float - 浮点值
### getHyphenSymbol() {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```


获取或设置在断字过程中使用的连字符。

--------------------

要消除连字符绘制（换行过程仍然存在），请为 HyphenSymbol 设置空字符串 string.Empty。

**退货：**
java.lang.String - 字符串值
### getLineSpacing() {#getLineSpacing--}
```
public int getLineSpacing()
```


获取行距模式。默认值为 LineSpacingMode.FontSize

**退货：**
int - 整数值
### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


获取或设置后续行缩进值。

**退货：**
float - 浮点值
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取自动换行模式。默认值为 WordWrapMode.NoWrap

**退货：**
int - WordWrapMode 值
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




### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


获取或设置首行缩进值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public final void setHyphenSymbol(String value)
```


获取或设置在断字过程中使用的连字符。

--------------------

要消除连字符绘制（换行过程仍然存在），请为 HyphenSymbol 设置空字符串 string.Empty。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 值 字符串值 |

### setLineSpacing(int value) {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```


设置行距模式。默认值为 LineSpacingMode.FontSize

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


获取或设置后续行缩进值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


设置自动换行模式。默认值为 WordWrapMode.NoWrap

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | WordWrapMode 值 |

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
