---
title: Path
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表圆弧。
type: docs
weight: 18
url: /zh/java/com.aspose.pdf.drawing/path/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.drawing.Shape](../../com.aspose.pdf.drawing/shape)
```
public final class Path extends Shape
```

代表圆弧。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Path(Shape[] shapes)](#Path-com.aspose.pdf.drawing.Shape---) | 初始化 Path 类的新实例。 |
| [Path()](#Path--) | 初始化 Path 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | 获取指示图形信息的对象，如颜色、线宽等。 |
| [getShapes()](#getShapes--) | 获取或设置形状集合。 |
| [getShapesInternal()](#getShapesInternal--) | 获取或设置形状集合。 |
| [getText()](#getText--) | 获取或设置形状的文本 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | 设置指示图形信息的对象，如颜色、线宽等。 |
| [setText(TextFragment value)](#setText-com.aspose.pdf.TextFragment-) | 获取或设置形状的文本 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Path(Shape[] shapes) {#Path-com.aspose.pdf.drawing.Shape---}
```
public Path(Shape[] shapes)
```


初始化 Path 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.pdf.drawing/shape) | 形状数组包含路径段集。 |

### Path() {#Path--}
```
public Path()
```


初始化 Path 类的新实例。

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
### getShapes() {#getShapes--}
```
public List<Shape> getShapes()
```


获取或设置形状集合。

**退货：**
java.util.List<com.aspose.pdf.drawing.Shape> - java.util.List 对象
### getShapesInternal() {#getShapesInternal--}
```
public System.Collections.Generic.List<Shape> getShapesInternal()
```


获取或设置形状集合。

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.drawing.Shape> - 内部对象
### getText() {#getText--}
```
public TextFragment getText()
```


获取或设置形状的文本

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) TextFragment 对象
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
