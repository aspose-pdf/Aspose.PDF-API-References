---
title: TextExtractionOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本提取选项
type: docs
weight: 370
url: /zh/java/com.aspose.pdf/textextractionoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextExtractionOptions extends TextOptions
```

表示文本提取选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextExtractionOptions(int formattingMode)](#TextExtractionOptions-int-) | 为指定的文本格式化模式初始化 TextExtractionOptions 对象的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormattingMode()](#getFormattingMode--) | 获取格式化模式。 |
| [getScaleFactor()](#getScaleFactor--) | 获取在纯模式下提取期间将应用于缩放字体大小的因子。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormattingMode(int value)](#setFormattingMode-int-) | 设置格式化模式。 |
| [setScaleFactor(double value)](#setScaleFactor-double-) | 设置在纯模式下提取期间将应用于缩放字体大小的因子。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextExtractionOptions(int formattingMode) {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```


为指定的文本格式化模式初始化 TextExtractionOptions 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattingMode | int | 文本格式化模式值。 |

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
### getFormattingMode() {#getFormattingMode--}
```
public int getFormattingMode()
```


获取格式化模式。

**退货：**
int - TextFormattingMode 值
### getScaleFactor() {#getScaleFactor--}
```
public double getScaleFactor()
```


获取在纯模式下提取期间将应用于缩放字体大小的因子。设置较小的值会导致提取的文本中出现更多空格。默认值为 1 - 无缩放；将值设置为零允许算法自动选择缩放比例。

**退货：**
双倍价值
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




### setFormattingMode(int value) {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```


设置格式化模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | TextFormattingMode 值 |

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```


设置在纯模式下提取期间将应用于缩放字体大小的因子。设置较小的值会导致提取文本中有更多空格（从 1 到 10）。默认值为 1 - 无缩放；将值设置为零允许算法自动选择缩放比例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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
