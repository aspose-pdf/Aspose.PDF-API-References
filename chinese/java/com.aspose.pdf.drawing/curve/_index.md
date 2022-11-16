---
title: Curve
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示贝塞尔曲线。
type: docs
weight: 12
url: /zh/java/com.aspose.pdf.drawing/curve/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.drawing.Shape](../../com.aspose.pdf.drawing/shape)
```
public final class Curve extends Shape
```

表示贝塞尔曲线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Curve()](#Curve--) | 仅供内部使用 |
| [Curve(float[] positionArray)](#Curve-float---) | 初始化 Curve 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | 获取指示图形信息的对象，如颜色、线宽等。 |
| [getPositionArray()](#getPositionArray--) | 获取一个浮动位置数组。 |
| [getText()](#getText--) | 获取或设置形状的文本 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | 设置指示图形信息的对象，如颜色、线宽等。 |
| [setPositionArray(float[] value)](#setPositionArray-float---) | 设置浮动位置数组。 |
| [setText(TextFragment value)](#setText-com.aspose.pdf.TextFragment-) | 获取或设置形状的文本 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Curve() {#Curve--}
```
public Curve()
```


仅供内部使用

### Curve(float[] positionArray) {#Curve-float---}
```
public Curve(float[] positionArray)
```


初始化 Curve 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| positionArray | float[] | 曲线控制点的位置数组。应该有四个控制点，所以数组的长度应该是八。 |

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
### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


获取指示图形信息的对象，如颜色、线宽等。

**退货：**
[GraphInfo](../../com.aspose.pdf/graphinfo) 指示图形信息的对象。
### getPositionArray() {#getPositionArray--}
```
public float[] getPositionArray()
```


获取一个浮动位置数组。

**退货：**
漂浮[- 漂浮[大批
### getText() {#getText--}
```
public TextFragment getText()
```


获取或设置形状的文本

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment 对象
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




### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


设置指示图形信息的对象，如颜色、线宽等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | 指示图形信息。 |

### setPositionArray(float[] value) {#setPositionArray-float---}
```
public void setPositionArray(float[] value)
```


设置浮动位置数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | 漂浮[] | float[大批 |

### setText(TextFragment value) {#setText-com.aspose.pdf.TextFragment-}
```
public void setText(TextFragment value)
```


获取或设置形状的文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | 文本片段对象 |

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
