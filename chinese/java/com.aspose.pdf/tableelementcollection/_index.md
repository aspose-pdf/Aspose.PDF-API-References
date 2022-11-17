---
title: TableElementCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示从现有表中吸收的元素集合
type: docs
weight: 355
url: /zh/java/com.aspose.pdf/tableelementcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class TableElementCollection<T1> implements Iterable<T1>
```

表示从现有表中吸收的元素集合

 ：实现 ITableElement 类型的实例 
## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem(ITableElement element)](#addItem-com.aspose.pdf.ITableElement-) | 在指定索引处添加文本片段元素。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [containsItem(T1 item)](#containsItem-T1-) | 确定集合是否包含特定值。 |
| [copyToTArray(T1[] array, int index)](#copyToTArray-T1---int-) | 将整个集合复制到兼容的一维数组，从目标数组的指定索引开始 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对集合的访问的对象。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的文本片段元素。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | 返回整个集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(T1 item)](#removeItem-T1-) | 从集合中删除指定的项目。 |
| [size()](#size--) | 获取集合中实际包含的表元素的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(ITableElement element) {#addItem-com.aspose.pdf.ITableElement-}
```
public void addItem(ITableElement element)
```


在指定索引处添加文本片段元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [ITableElement](../../com.aspose.pdf/itableelement) | ITableElement 实例 |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### containsItem(T1 item) {#containsItem-T1-}
```
public boolean containsItem(T1 item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | T1 | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### copyToTArray(T1[] array, int index) {#copyToTArray-T1---int-}
```
public void copyToTArray(T1[] array, int index)
```


将整个集合复制到兼容的一维数组，从目标数组的指定索引开始

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | T1[] | 将被复制的对象数组。 |
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
java.lang.Object - SyncRoot 对象
### get_Item(int index) {#get-Item-int-}
```
public T1 get_Item(int index)
```


获取指定索引处的文本片段元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中的索引。 |

**退货：**
T1 - 表格元素对象。
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
public System.Collections.IEnumerator<T1> iterator()
```


返回整个集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<T1> - 枚举器对象。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


返回整个集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator - 枚举器对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeItem(T1 item) {#removeItem-T1-}
```
public boolean removeItem(T1 item)
```


从集合中删除指定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | T1 | 要删除的对象 |

**退货：**
布尔值 - 如果项目已从集合中删除，则为 true；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中实际包含的表元素的数量。

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
