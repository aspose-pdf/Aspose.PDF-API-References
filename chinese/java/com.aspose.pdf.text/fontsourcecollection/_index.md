---
title: FontSourceCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字体源集合。
type: docs
weight: 12
url: /zh/java/com.aspose.pdf.text/fontsourcecollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class FontSourceCollection implements Iterable<FontSource>
```

表示字体源集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSourceCollection()](#FontSourceCollection--) | 初始化集合对象 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged 事件 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(FontSource fontSource)](#add-com.aspose.pdf.FontSource-) | 将新的字体源对象添加到集合中。 |
| [clear()](#clear--) | 清除字体源集合。 |
| [contains(FontSource item)](#contains-com.aspose.pdf.FontSource-) | 确定元素是否在集合中。 |
| [copyTo(FontSource[] array, int index)](#copyTo-com.aspose.pdf.FontSource---int-) | 将整个集合复制到兼容的一维数组，从目标数组的指定索引开始 |
| [delete(FontSource fontSource)](#delete-com.aspose.pdf.FontSource-) | 删除字体源元素。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItem(int index)](#getItem-int-) | 获取指定索引处的字体元素。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对集合的访问的对象。 |
| [hashCode()](#hashCode--) |  |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(FontSource item)](#remove-com.aspose.pdf.FontSource-) | 删除字体源元素。 |
| [size()](#size--) | 获取集合中实际包含的 Font 对象元素的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontSourceCollection() {#FontSourceCollection--}
```
public FontSourceCollection()
```


初始化集合对象

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent<System.EventHandler> CollectionChanged
```


CollectionChanged 事件

### add(FontSource fontSource) {#add-com.aspose.pdf.FontSource-}
```
public void add(FontSource fontSource)
```


将新的字体源对象添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | 字体来源。 |

### clear() {#clear--}
```
public void clear()
```


清除字体源集合。

### contains(FontSource item) {#contains-com.aspose.pdf.FontSource-}
```
public boolean contains(FontSource item)
```


确定元素是否在集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | 要搜索的 FontSource 对象。 |

**退货：**
boolean - True - 如果找到元素；否则，假的。
### copyTo(FontSource[] array, int index) {#copyTo-com.aspose.pdf.FontSource---int-}
```
public void copyTo(FontSource[] array, int index)
```


将整个集合复制到兼容的一维数组，从目标数组的指定索引开始

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [FontSource\[\]](../../com.aspose.pdf/fontsource) | 将被复制的对象数组。 |
| index | int | 将从其开始复制的起始索引。 |

### delete(FontSource fontSource) {#delete-com.aspose.pdf.FontSource-}
```
public void delete(FontSource fontSource)
```


删除字体源元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | 将被删除的 FontSource 对象。 |

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
### getItem(int index) {#getItem-int-}
```
public FontSource getItem(int index)
```


获取指定索引处的字体元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中的索引。 |

**退货：**
[FontSource](../../com.aspose.pdf/fontsource) - 字体源对象。
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对集合的访问的对象。

**退货：**
java.lang.Object - 对象元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对集合的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
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




### remove(FontSource item) {#remove-com.aspose.pdf.FontSource-}
```
public boolean remove(FontSource item)
```


删除字体源元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | 将被删除的 FontSource 对象。 |

**退货：**
boolean - True - 如果找到元素；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中实际包含的 Font 对象元素的数量。

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
