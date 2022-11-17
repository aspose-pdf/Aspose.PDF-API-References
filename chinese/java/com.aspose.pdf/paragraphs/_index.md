---
title: Paragraphs
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示段落集合。
type: docs
weight: 270
url: /zh/java/com.aspose.pdf/paragraphs/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable，com.aspose.ms.System.ICloneable
```
public class Paragraphs implements Iterable<BaseParagraph>, System.ICloneable
```

此类表示段落集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Paragraphs()](#Paragraphs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(BaseParagraph paragraph)](#add-com.aspose.pdf.BaseParagraph-) | 将段落添加到集合中。 |
| [clear()](#clear--) | 清晰的段落。 |
| [deepClone()](#deepClone--) | 克隆一个新的 Clone 对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取段落计数。 |
| [getRange(int index, int count)](#getRange-int-int-) | 删除段落范围。 |
| [get_Item(int index)](#get-Item-int-) | 从集合中获取段落。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, BaseParagraph paragraph)](#insert-int-com.aspose.pdf.BaseParagraph-) | 将段落插入集合。 |
| [insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)](#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--) | 将集合的元素插入到指定索引处的列表中。 |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(BaseParagraph paragraph)](#remove-com.aspose.pdf.BaseParagraph-) | 从集合中删除段落。 |
| [removeRange(int index, int count)](#removeRange-int-int-) | 删除段落范围。 |
| [set_Item(int index, BaseParagraph value)](#set-Item-int-com.aspose.pdf.BaseParagraph-) | 将段落设置为集合。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Paragraphs() {#Paragraphs--}
```
public Paragraphs()
```


### add(BaseParagraph paragraph) {#add-com.aspose.pdf.BaseParagraph-}
```
public void add(BaseParagraph paragraph)
```


将段落添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | 这段落。 |

### clear() {#clear--}
```
public void clear()
```


清晰的段落。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆一个新的 Clone 对象。

**退货：**
java.lang.Object - 新的 Clone 对象。
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
### getCount() {#getCount--}
```
public int getCount()
```


获取段落计数。

**退货：**
int - 整数值
### getRange(int index, int count) {#getRange-int-int-}
```
public Paragraphs getRange(int index, int count)
```


删除段落范围。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 第一段索引。 |
| count | int | 段落很重要。 |

**退货：**
[Paragraphs](../../com.aspose.pdf/paragraphs) 段落集合
### get_Item(int index) {#get-Item-int-}
```
public BaseParagraph get_Item(int index)
```


从集合中获取段落。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 段落索引。 |

**退货：**
[BaseParagraph](../../com.aspose.pdf/baseparagraph) - BaseParagraph 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(int index, BaseParagraph paragraph) {#insert-int-com.aspose.pdf.BaseParagraph-}
```
public void insert(int index, BaseParagraph paragraph)
```


将段落插入集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 段落的索引。 |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | 这段落。 |

### insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection) {#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--}
```
public void insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)
```


将集合的元素插入到指定索引处的列表中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值（索引） |
| collection | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.BaseParagraph> | BaseParagraph 对象列表（集合） |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```




**退货：**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(BaseParagraph paragraph) {#remove-com.aspose.pdf.BaseParagraph-}
```
public void remove(BaseParagraph paragraph)
```


从集合中删除段落。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | BaseParagraph 对象 |

### removeRange(int index, int count) {#removeRange-int-int-}
```
public void removeRange(int index, int count)
```


删除段落范围。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 第一段索引。 |
| count | int | 段落很重要。 |

### set_Item(int index, BaseParagraph value) {#set-Item-int-com.aspose.pdf.BaseParagraph-}
```
public void set_Item(int index, BaseParagraph value)
```


将段落设置为集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 段落索引。 |
| value | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | BaseParagraph 对象 |

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
