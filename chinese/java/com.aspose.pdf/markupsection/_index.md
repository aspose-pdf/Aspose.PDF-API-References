---
title: MarkupSection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示标记部分 - 页面的矩形区域，其中包含文本并且可以在视觉上与其他文本块分开。
type: docs
weight: 208
url: /zh/java/com.aspose.pdf/markupsection/
---
**遗产：**
java.lang.Object
```
public final class MarkupSection
```

表示标记部分 - 页面的矩形区域，其中包含文本并且可以在视觉上与其他文本块分开。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFragments()](#getFragments--) | 该部分内的非空 TextFragment 对象的集合。 |
| [getParagraphs()](#getParagraphs--) | 节内的 MarkupParagraph 对象的集合。 |
| [getRectangle()](#getRectangle--) | 剖面矩形 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


该部分内的非空 TextFragment 对象的集合。

--------------------

TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

**退货：**
java.util.List<com.aspose.pdf.TextFragment> - TextFragment 实例列表
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


节内的 MarkupParagraph 对象的集合。

**退货：**
java.util.List<com.aspose.pdf.MarkupParagraph> - MarkupParagraph 实例列表
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


剖面矩形

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形实例
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
