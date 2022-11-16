---
title: TextParagraphCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个文本段落集合
type: docs
weight: 382
url: /zh/java/com.aspose.pdf/textparagraphcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class TextParagraphCollection implements Iterable<TextParagraph>
```

表示一个文本段落集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(TextParagraph paragraph)](#add-com.aspose.pdf.TextParagraph-) | 在指定索引处添加文本段落元素。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(TextParagraph item)](#contains-com.aspose.pdf.TextParagraph-) | 确定集合是否包含特定值。 |
| [copyTo(TextParagraph[] array, int index)](#copyTo-com.aspose.pdf.TextParagraph---int-) | 将整个集合复制到兼容的一维数组，从目标数组的指定索引开始 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对集合的访问的对象。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的文本段落元素。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(TextParagraph item)](#remove-com.aspose.pdf.TextParagraph-) | 从集合中删除指定的项目。 |
| [size()](#size--) | 获取集合中实际包含的 TextParagraph 对象元素的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(TextParagraph paragraph) {#add-com.aspose.pdf.TextParagraph-}
```
public void add(TextParagraph paragraph)
```


在指定索引处添加文本段落元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | 文本段落实例 |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(TextParagraph item) {#contains-com.aspose.pdf.TextParagraph-}
```
public boolean contains(TextParagraph item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [TextParagraph](../../com.aspose.pdf/textparagraph) | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### copyTo(TextParagraph[] array, int index) {#copyTo-com.aspose.pdf.TextParagraph---int-}
```
public void copyTo(TextParagraph[] array, int index)
```


将整个集合复制到兼容的一维数组，从目标数组的指定索引开始

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [TextParagraph\[\]](../../com.aspose.pdf/textparagraph) | 数组集合 |
| index | int | 整数值 |

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
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对集合的访问的对象。

**退货：**
java.lang.Object - 对象元素
### get_Item(int index) {#get-Item-int-}
```
public TextParagraph get_Item(int index)
```


获取指定索引处的文本段落元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |

**退货：**
[TextParagraph](../../com.aspose.pdf/textparagraph) 文本段落对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对集合的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<TextParagraph> iterator()
```


返回整个集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.TextParagraph> - IEnumerator 对象
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(TextParagraph item) {#remove-com.aspose.pdf.TextParagraph-}
```
public boolean remove(TextParagraph item)
```


从集合中删除指定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [TextParagraph](../../com.aspose.pdf/textparagraph) | 要删除的对象 |

**退货：**
布尔值 - 如果项目已从集合中删除，则为 true；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中实际包含的 TextParagraph 对象元素的数量。

**退货：**
int - 整数值
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
