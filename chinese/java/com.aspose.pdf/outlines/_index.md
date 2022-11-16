---
title: Outlines
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类描述大纲的集合。
type: docs
weight: 241
url: /zh/java/com.aspose.pdf/outlines/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public abstract class Outlines implements Iterable<OutlineItemCollection>
```

类描述大纲的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Outlines()](#Outlines--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(OutlineItemCollection item)](#add-com.aspose.pdf.OutlineItemCollection-) | 将大纲项添加到集合中。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | 总是抛出 NotImplementedException。 |
| [copyTo(OutlineItemCollection[] array, int arrayIndex)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | 将大纲条目复制到 System.Array，从特定的 System.Array 索引开始。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getVisibleCount()](#getVisibleCount--) | 获取文档大纲层次结构中所有级别的大纲项总数。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [iterator()](#iterator--) | 返回循环访问集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | 删除大纲集合项。 |
| [size()](#size--) | 得到计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Outlines() {#Outlines--}
```
public Outlines()
```


### add(OutlineItemCollection item) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public abstract void add(OutlineItemCollection item)
```


将大纲项添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要添加的大纲项目。 |

### clear() {#clear--}
```
public abstract void clear()
```


清除集合中的所有项目。

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public abstract boolean contains(OutlineItemCollection item)
```


总是抛出 NotImplementedException。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要在集合中定位的对象 |

**退货：**
boolean - 布尔值 True - 如果找到项目；否则，假的。
### copyTo(OutlineItemCollection[] array, int arrayIndex) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public abstract void copyTo(OutlineItemCollection[] array, int arrayIndex)
```


将大纲条目复制到 System.Array，从特定的 System.Array 索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | 作为目标的一维 System.Array。必须具有从零开始的索引。 |
| arrayIndex | int | array 中从零开始的索引，复制从这里开始。 |

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
### getVisibleCount() {#getVisibleCount--}
```
public abstract int getVisibleCount()
```


获取文档大纲层次结构中所有级别的大纲项总数。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public abstract Iterator<OutlineItemCollection> iterator()
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
public abstract boolean remove(OutlineItemCollection item)
```


删除大纲集合项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要删除的项目。 |

**退货：**
boolean - 布尔值 True - 如果项目被移除；否则，假的。
### size() {#size--}
```
public abstract int size()
```


得到计数。

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
