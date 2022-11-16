---
title: PageInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 pdf 生成器的页面信息。
type: docs
weight: 261
url: /zh/java/com.aspose.pdf/pageinfo/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.ICloneable
```
public class PageInfo implements System.ICloneable
```

表示 pdf 生成器的页面信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageInfo()](#PageInfo--) | 默认构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆页面信息。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnyMargin()](#getAnyMargin--) | 获取或设置除第一页以外的任何页面的页边距。 |
| [getClass()](#getClass--) |  |
| [getDefaultTextState()](#getDefaultTextState--) | 获取默认字体。 |
| [getHeight()](#getHeight--) | 获取页面高度。 |
| [getMargin()](#getMargin--) | 获取页边距。 |
| [getPureHeight()](#getPureHeight--) | 获取没有边距的页面纯高。 |
| [getWidth()](#getWidth--) | 获取页面宽度。 |
| [hashCode()](#hashCode--) |  |
| [isLandscape()](#isLandscape--) | 得到的是页面美化。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAnyMargin(MarginInfo value)](#setAnyMargin-com.aspose.pdf.MarginInfo-) | 获取或设置除第一页以外的任何页面的页边距。 |
| [setDefaultTextState(TextState value)](#setDefaultTextState-com.aspose.pdf.TextState-) | 设置默认字体。 |
| [setHeight(double value)](#setHeight-double-) | 设置页面高度。 |
| [setLandscape(boolean value)](#setLandscape-boolean-) | 设置页面美化。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置页边距。 |
| [setWidth(double value)](#setWidth-double-) | 设置页面宽度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PageInfo() {#PageInfo--}
```
public PageInfo()
```


默认构造函数

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆页面信息。

**退货：**
java.lang.Object - 克隆的对象
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
### getAnyMargin() {#getAnyMargin--}
```
public final MarginInfo getAnyMargin()
```


获取或设置除第一页以外的任何页面的页边距。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDefaultTextState() {#getDefaultTextState--}
```
public TextState getDefaultTextState()
```


获取默认字体。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取页面高度。

**退货：**
双倍价值
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取页边距。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getPureHeight() {#getPureHeight--}
```
public double getPureHeight()
```


获取没有边距的页面纯高。

**退货：**
双倍价值
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取页面宽度。

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


得到的是页面美化。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAnyMargin(MarginInfo value) {#setAnyMargin-com.aspose.pdf.MarginInfo-}
```
public final void setAnyMargin(MarginInfo value)
```


获取或设置除第一页以外的任何页面的页边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setDefaultTextState(TextState value) {#setDefaultTextState-com.aspose.pdf.TextState-}
```
public void setDefaultTextState(TextState value)
```


设置默认字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态实例 |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置页面高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setLandscape(boolean value) {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```


设置页面美化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置页边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 值 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置页面宽度。

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
