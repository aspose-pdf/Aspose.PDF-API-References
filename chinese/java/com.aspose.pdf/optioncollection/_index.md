---
title: OptionCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示选择字段的选项集合的类。
type: docs
weight: 238
url: /zh/java/com.aspose.pdf/optioncollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class OptionCollection implements Iterable<Option>
```

表示选择字段的选项集合的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Option item)](#add-com.aspose.pdf.Option-) | 在集合中添加项目，抛出。 |
| [clear()](#clear--) | 从集合中移除所有项目，抛出。 |
| [contains(Option item)](#contains-com.aspose.pdf.Option-) | 检查项目是否存在于集合中，抛出。 |
| [deleteOption(String name)](#deleteOption-java.lang.String-) | 按名称删除选项。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 按索引获取选项。 |
| [get(String name)](#get-java.lang.String-) | 通过选项名称从集合中获取选项。 |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 集合的同步对象。 |
| [get_Item(int index)](#get-Item-int-) | 按索引获取选项。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过名称获取选项。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 返回 true 的对象是同步的。 |
| [iterator()](#iterator--) | 返回集合中选项的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | 返回集合中选项的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Option item)](#remove-com.aspose.pdf.Option-) | 从集合中移除项目，抛出。 |
| [size()](#size--) | 获取选项数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Option item) {#add-com.aspose.pdf.Option-}
```
public void add(Option item)
```


在集合中添加项目，抛出。

尚未实施。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | 期权实例 |

### clear() {#clear--}
```
public void clear()
```


从集合中移除所有项目，抛出。

尚未实施。

### contains(Option item) {#contains-com.aspose.pdf.Option-}
```
public boolean contains(Option item)
```


检查项目是否存在于集合中，抛出。

尚未实施。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | 期权实例 |

**退货：**
boolean - 布尔值
### deleteOption(String name) {#deleteOption-java.lang.String-}
```
public void deleteOption(String name)
```


按名称删除选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的选项的名称。 |

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
### get(int index) {#get-int-}
```
public Option get(int index)
```


按索引获取选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 期权指数。指数应该在范围内[1..n] 其中 n 是选项计数。 |

**退货：**
[Option](../../com.aspose.pdf/option) - 检索选项。
### get(String name) {#get-java.lang.String-}
```
public Option get(String name)
```


通过选项名称从集合中获取选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 选项名称。 |

**退货：**
[Option](../../com.aspose.pdf/option) - 检索选项。
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


集合的同步对象。

**退货：**
java.lang.Object - 对象元素
### get_Item(int index) {#get-Item-int-}
```
public Option get_Item(int index)
```


按索引获取选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 选项的索引。 |

**退货：**
[Option](../../com.aspose.pdf/option) - 指定索引上的选项。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Option get_Item(String name)
```


通过名称获取选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 选项的名称。 |

**退货：**
[Option](../../com.aspose.pdf/option) - 找到选项。
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


返回 true 的对象是同步的。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<Option> iterator()
```


返回集合中选项的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.Option> - 选项枚举器。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


返回集合中选项的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator - 选项枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Option item) {#remove-com.aspose.pdf.Option-}
```
public boolean remove(Option item)
```


从集合中移除项目，抛出。

尚未实施。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Option](../../com.aspose.pdf/option) | 期权实例 |

**退货：**
boolean - 布尔值
### size() {#size--}
```
public int size()
```


获取选项数。

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
