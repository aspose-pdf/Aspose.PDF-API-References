---
title: FontAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字体的吸收器对象。
type: docs
weight: 131
url: /zh/java/com.aspose.pdf/fontabsorber/
---
**遗产：**
java.lang.Object
```
public class FontAbsorber
```

表示字体的吸收器对象。执行字体搜索并通过 FontAbsorber.Fonts 集合提供对搜索结果的访问。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontAbsorber()](#FontAbsorber--) | 初始化执行文档字体搜索的 FontAbsorber 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | 获取与 Font 对象一起出现的搜索事件的集合。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(Document pdf)](#visit-com.aspose.pdf.Document-) | 对指定文档执行搜索。 |
| [visit(Document pdf, int startPage, int pageCount)](#visit-com.aspose.pdf.Document-int-int-) | 在文档的指定页面范围内执行搜索。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontAbsorber() {#FontAbsorber--}
```
public FontAbsorber()
```


初始化执行文档字体搜索的 FontAbsorber 的新实例。

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
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


获取与 Font 对象一起出现的搜索事件的集合。

**退货：**
[FontCollection](../../com.aspose.pdf/fontcollection) - 字体集合对象
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
### visit(Document pdf) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document pdf)
```


对指定文档执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf 文档对象。 |

### visit(Document pdf, int startPage, int pageCount) {#visit-com.aspose.pdf.Document-int-int-}
```
public void visit(Document pdf, int startPage, int pageCount)
```


在文档的指定页面范围内执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf 文档对象。 |
| startPage | int | Pdf 文档起始页。 |
| pageCount | int | PDF文档页数 |

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
