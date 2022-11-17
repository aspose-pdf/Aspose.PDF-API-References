---
title: ActionCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 动作集合
type: docs
weight: 14
url: /zh/java/com.aspose.pdf/actioncollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class ActionCollection implements Iterable<PdfAction>
```

动作集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | 将新动作添加到集合中。 |
| [clear()](#clear--) | 清除集合。 |
| [contains(PdfAction item)](#contains-com.aspose.pdf.PdfAction-) | 尚不支持。 |
| [copyTo(PdfAction[] array, int index)](#copyTo-com.aspose.pdf.PdfAction---int-) | 将操作数组复制到集合中。 |
| [delete()](#delete--) | 删除所有动作。 |
| [delete(int index)](#delete-int-) | 按索引从集合中删除操作。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取同步对象。 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取操作。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 如果集合是只读的，则返回 true。 |
| [isSynchronized()](#isSynchronized--) | 如果对象已同步，则返回 true。 |
| [iterator()](#iterator--) | 返回集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PdfAction item)](#remove-com.aspose.pdf.PdfAction-) | \* 尚不支持。 |
| [size()](#size--) | 对集合的操作计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


将新动作添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | 应添加的操作。 |

### clear() {#clear--}
```
public void clear()
```


清除集合。

### contains(PdfAction item) {#contains-com.aspose.pdf.PdfAction-}
```
public boolean contains(PdfAction item)
```


尚不支持。

如果集合中存在给定项，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 实例未实现。 |

**退货：**
boolean - 要查找的布尔值项目。
### copyTo(PdfAction[] array, int index) {#copyTo-com.aspose.pdf.PdfAction---int-}
```
public void copyTo(PdfAction[] array, int index)
```


将操作数组复制到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [PdfAction\[\]](../../com.aspose.pdf/pdfaction) | 必须复制到集合中的操作数组。 |
| index | int | 将从哪个数组开始复制的索引。 |

### delete() {#delete--}
```
public void delete()
```


删除所有动作。

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


按索引从集合中删除操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的操作索引。 |

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


获取同步对象。

**退货：**
java.lang.Object - 对象值
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


通过其索引获取操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 行动指数。 |

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) - 收回行动。
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


如果集合是只读的，则返回 true。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


如果对象已同步，则返回 true。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<PdfAction> iterator()
```


返回集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> - 集合枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PdfAction item) {#remove-com.aspose.pdf.PdfAction-}
```
public boolean remove(PdfAction item)
```


\* 尚不支持。

从集合中删除项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | 要删除的项目。 |

**退货：**
boolean - 布尔值 未实现。
### size() {#size--}
```
public int size()
```


对集合的操作计数。

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
