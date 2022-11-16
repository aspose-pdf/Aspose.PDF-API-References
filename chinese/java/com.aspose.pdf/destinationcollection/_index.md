---
title: DestinationCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示所有目的地的集合，名称树将名称字符串映射到目的地，请参阅 pdf 文档中的 12.3.2.3 命名目的地和 7.7.4 名称字典。
type: docs
weight: 84
url: /zh/java/com.aspose.pdf/destinationcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class DestinationCollection implements Iterable<System.Collections.Generic.KeyValuePair<String,Object>>
```

类表示 pdf 文档中所有目的地的集合（名称树将名称字符串映射到目的地（参见 12.3.2.3，“命名目的地”）和（参见 7.7.4，“名称字典”））。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(System.Collections.Generic.KeyValuePair<String,Object> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | 添加指定的项目。 |
| [clear()](#clear--) | 集合是只读的。 |
| [contains(System.Collections.Generic.KeyValuePair<String,Object> value)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | 确定此实例是否包含该对象。 |
| [copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-) | 将集合的元素复制到一个数组，从特定的数组索引开始。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExplicitDestination(String destinameName, boolean useCache)](#getExplicitDestination-java.lang.String-boolean-) | 按名称返回显式目的地。 |
| [getPageNumber(String destinameName, boolean useCache)](#getPageNumber-java.lang.String-boolean-) | 按名称返回目的地的页码。 |
| [get_Item(int index)](#get-Item-int-) | 通过索引获取目标对象。 |
| [hashCode()](#hashCode--) |  |
| [indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | 返回集合中目标的索引。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [iterator()](#iterator--) | 返回枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(System.Collections.Generic.KeyValuePair<String,Object> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | 删除指定的项目。 |
| [size()](#size--) | 获取集合中包含的元素数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(System.Collections.Generic.KeyValuePair<String,Object> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public void add(System.Collections.Generic.KeyValuePair<String,Object> item)
```


添加指定的项目。集合是只读的。总是抛出 NotSupportedException 异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | 该项目。 |

### clear() {#clear--}
```
public void clear()
```


集合是只读的。总是抛出 NotSupportedException 异常。

### contains(System.Collections.Generic.KeyValuePair<String,Object> value) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean contains(System.Collections.Generic.KeyValuePair<String,Object> value)
```


确定此实例是否包含该对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | 要查找的值。 |

**退货：**
布尔值 - 如果为真[包含][指定值];否则，假的。
### copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-}
```
public void copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)
```


将集合的元素复制到一个数组，从特定的数组索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>[] | 作为从集合中复制的元素的目的地的一维数组 |
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
### getExplicitDestination(String destinameName, boolean useCache) {#getExplicitDestination-java.lang.String-boolean-}
```
public ExplicitDestination getExplicitDestination(String destinameName, boolean useCache)
```


按名称返回显式目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destinameName | java.lang.String | 目的地名称。 |
| useCache | boolean | 确定是否使用缓存版本的集合。 |

**退货：**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - 找到目标的 ExplicitDestination 对象；否则为空。
### getPageNumber(String destinameName, boolean useCache) {#getPageNumber-java.lang.String-boolean-}
```
public int getPageNumber(String destinameName, boolean useCache)
```


按名称返回目的地的页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destinameName | java.lang.String | 目的地名称。 |
| useCache | boolean | 确定是否使用缓存版本的集合。 |

**退货：**
int - 找到目标时的页码；否则，-1。
### get_Item(int index) {#get-Item-int-}
```
public System.Collections.Generic.KeyValuePair<String,Object> get_Item(int index)
```


通过索引获取目标对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的目标索引。 |

**退货：**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - 目的地。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### indexOf(System.Collections.Generic.KeyValuePair<String,Object> value) {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public int indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)
```


返回集合中目标的索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | 要查找的值。 |

**退货：**
int - 集合中目标的索引。
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


返回枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - 枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(System.Collections.Generic.KeyValuePair<String,Object> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean remove(System.Collections.Generic.KeyValuePair<String,Object> item)
```


删除指定的项目。集合是只读的。总是抛出 NotSupportedException 异常。

还不支持。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | 该项目。 |

**退货：**
boolean - 布尔值
### size() {#size--}
```
public int size()
```


获取集合中包含的元素数。

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
