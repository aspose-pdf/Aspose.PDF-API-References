---
title: OutlineCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文档大纲层次结构。
type: docs
weight: 239
url: /zh/java/com.aspose.pdf/outlinecollection/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineCollection extends Outlines
```

表示文档大纲层次结构。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | 将大纲项添加到集合中。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。 |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | 将大纲项复制到 System.Array，从特定的 System.Array 索引开始。 |
| [delete()](#delete--) | 从文档大纲中删除所有大纲项。 |
| [delete(String name)](#delete-java.lang.String-) | 从文档大纲中删除具有指定标题的大纲项。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirst()](#getFirst--) | 获取表示大纲中第一个顶级项的大纲项。 |
| [getLast()](#getLast--) | 获取表示大纲中最后一个顶级项目的大纲项目。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对此集合的访问的对象。 |
| [getVisibleCount()](#getVisibleCount--) | 计数是各级可见的后代大纲项数的总和。 |
| [get_Item(int index)](#get-Item-int-) | 按索引从集合中获取大纲项。 |
| [hasNext()](#hasNext--) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对此集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回循环访问集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。 |
| [remove(int index)](#remove-int-) | 按索引删除项目。 |
| [size()](#size--) | 获取文档大纲所有级别的大纲项（书签）总数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


将大纲项添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要添加的大纲项目。 |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


尚不支持。

检查集合是否包含给定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要在集合中定位的对象 |

**退货：**
boolean - 布尔值 True - 如果找到项目；否则，假的。
### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


将大纲项复制到 System.Array，从特定的 System.Array 索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | 作为目标的一维 System.Array。必须具有从零开始的索引。 |
| index | int | array 中从零开始的索引，复制从这里开始。 |

### delete() {#delete--}
```
public void delete()
```


从文档大纲中删除所有大纲项。

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


从文档大纲中删除具有指定标题的大纲项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的大纲项目的标题 |

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
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


获取表示大纲中第一个顶级项的大纲项。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 对象
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


获取表示大纲中最后一个顶级项目的大纲项目。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 对象
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对此集合的访问的对象。

**退货：**
java.lang.Object - 同步对象
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


计数是各级可见的后代大纲项数的总和。注意：请不要与 Count 混淆，Count 是集合中的项目数。

**退货：**
整数
### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


按索引从集合中获取大纲项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 请求项的索引。 |

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 对象
### hasNext() {#hasNext--}
```
public boolean hasNext()
```




**退货：**
布尔值
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


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对此集合的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


返回循环访问集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> - 一个 System.Collections.IEnumerator 对象，可用于遍历集合。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**退货：**
com.aspose.ms.System.Collections.IEnumerator
### next() {#next--}
```
public OutlineItemCollection next()
```




**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public boolean remove(OutlineItemCollection item)
```


尚不支持。

总是抛出异常

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要在集合中定位的对象 |

**退货：**
boolean - 布尔值 True - 如果项目被移除；否则，假的。
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


按索引删除项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的项目的索引。 |

### size() {#size--}
```
public int size()
```


获取文档大纲所有级别的大纲项（书签）总数。

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
