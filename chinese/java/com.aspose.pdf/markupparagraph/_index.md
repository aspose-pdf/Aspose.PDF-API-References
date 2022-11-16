---
title: MarkupParagraph
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表一个段落。
type: docs
weight: 207
url: /zh/java/com.aspose.pdf/markupparagraph/
---
**遗产：**
java.lang.Object
```
public final class MarkupParagraph
```

代表一个段落。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContinuationPageNumbers()](#getContinuationPageNumbers--) | 段落继续的页码列表。 |
| [getFragments()](#getFragments--) | 段落的非空 TextFragment 对象的集合。 |
| [getLines()](#getLines--) | 段落的行数。 |
| [getPoints()](#getPoints--) | 描述段落的多边形点。 |
| [getSecondaryPoints()](#getSecondaryPoints--) | 次要多边形的点描述了段落的延续。 |
| [getText()](#getText--) | 获取 MarkupParagraph 对象表示的字符串文本对象。 |
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
### getContinuationPageNumbers() {#getContinuationPageNumbers--}
```
public final List<Integer> getContinuationPageNumbers()
```


段落继续的页码列表。如果它在同一页的下一列中继续，它将与段落开始的页面匹配。

**退货：**
java.util.List<java.lang.Integer> - 整数列表
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


段落的非空 TextFragment 对象的集合。

--------------------

TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

**退货：**
java.util.List<com.aspose.pdf.TextFragment> - TextFragment 实例列表
### getLines() {#getLines--}
```
public List<System.Collections.Generic.List<TextFragment>> getLines()
```


段落的行数。每行由文本片段列表表示。

--------------------

TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

**退货：**
java.util.List<com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.TextFragment>> - TextFragment 实例列表
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


描述段落的多边形点。起点是段落的左下角。接下来的点是逆时针顺序。

**退货：**
com.aspose.pdf.点[] - 点实例数组
### getSecondaryPoints() {#getSecondaryPoints--}
```
public final List<Point[]> getSecondaryPoints()
```


次要多边形的点描述了段落的延续。如果该段落在下一列或页面中继续，则它不会为空。起点是段落的左下角。接下来的点是逆时针顺序。

**退货：**
java.util.List<com.aspose.pdf.Point[]> - 点列表[]
### getText() {#getText--}
```
public String getText()
```


获取 MarkupParagraph 对象表示的字符串文本对象。

**退货：**
java.lang.String - 字符串值
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
