---
title: TextFragmentCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本片段集合
type: docs
weight: 374
url: /zh/java/com.aspose.pdf/textfragmentcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class TextFragmentCollection implements Iterable<TextFragment>
```

表示文本片段集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(TextFragment fragment)](#add-com.aspose.pdf.TextFragment-) | 在指定索引处添加文本片段元素。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(TextFragment item)](#contains-com.aspose.pdf.TextFragment-) | 确定集合是否包含特定值。 |
| [copyTo(TextFragment[] array, int index)](#copyTo-com.aspose.pdf.TextFragment---int-) | 将整个集合复制到兼容的一维数组，从目标数组的指定索引开始 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对集合的访问的对象。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的文本片段元素。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(TextFragment item)](#remove-com.aspose.pdf.TextFragment-) | 从集合中删除指定的项目。 |
| [size()](#size--) | 获取集合中实际包含的 TextFragment 对象元素的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(TextFragment fragment) {#add-com.aspose.pdf.TextFragment-}
```
public void add(TextFragment fragment)
```


在指定索引处添加文本片段元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | 要添加的 TextFragment 对象元素。 |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(TextFragment item) {#contains-com.aspose.pdf.TextFragment-}
```
public boolean contains(TextFragment item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### copyTo(TextFragment[] array, int index) {#copyTo-com.aspose.pdf.TextFragment---int-}
```
public void copyTo(TextFragment[] array, int index)
```


将整个集合复制到兼容的一维数组，从目标数组的指定索引开始

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [TextFragment\[\]](../../com.aspose.pdf/textfragment) | 将被复制的对象数组。 |
| index | int | 将从其开始复制的起始索引。 |

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
public TextFragment get_Item(int index)
```


获取指定索引处的文本片段元素。

索引应该在范围内[1..n] 其中 n 等于文本片段数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中的索引。 |

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment 对象。
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
public Iterator<TextFragment> iterator()
```


返回整个集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.TextFragment> - 枚举器对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(TextFragment item) {#remove-com.aspose.pdf.TextFragment-}
```
public boolean remove(TextFragment item)
```


从集合中删除指定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | 要删除的对象 |

**退货：**
布尔值 - 如果项目已从集合中删除，则为 true；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中实际包含的 TextFragment 对象元素的数量。

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
