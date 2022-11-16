---
title: BaseOperatorCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示运算符集合的基类。
type: docs
weight: 33
url: /zh/java/com.aspose.pdf/baseoperatorcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public abstract class BaseOperatorCollection implements Iterable<Operator>
```

表示运算符集合的基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseOperatorCollection()](#BaseOperatorCollection--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | 将新运算符添加到集合中。 |
| [cancelUpdate()](#cancelUpdate--) | 取消上次更新。 |
| [clear()](#clear--) | 清除集合。 |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) | 检查该项目是否在收藏中。 |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | 内部的 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | 仅供内部使用 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取运算符。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | 将运算符插入集合。 |
| [isEmpty()](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | 指示集合是否仅限于快速文本提取 |
| [isReadOnly()](#isReadOnly--) | 如果集合是只读的，则返回 true。 |
| [iterator()](#iterator--) | 返回集合的枚举器 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) | 从集合中移除运算符。 |
| [resumeUpdate()](#resumeUpdate--) | 恢复文档更新。 |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | 通过索引设置运算符。 |
| [size()](#size--) | 获取集合中运算符的计数。 |
| [suppressUpdate()](#suppressUpdate--) | 抑制更新内容数据。 |
| [toList()](#toList--) | 返回操作者列表。 |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | 内部的 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseOperatorCollection() {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```


### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public abstract void add(Operator op)
```


将新运算符添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 必须添加的运算符 |

### cancelUpdate() {#cancelUpdate--}
```
public abstract void cancelUpdate()
```


取消上次更新。当更改不应该引发内容更新时，可以调用此方法。

### clear() {#clear--}
```
public abstract void clear()
```


清除集合。

### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public abstract boolean contains(Operator item)
```


检查该项目是否在收藏中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | 要查找的运算符实例项。 |

**退货：**
boolean - 布尔值 True - 如果找到项目；否则，假的。
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```


内部的

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
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
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |

**退货：**
[Operator](../../com.aspose.pdf/operator) - 操作员对象
### get_Item(int index) {#get-Item-int-}
```
public abstract Operator get_Item(int index)
```


通过其索引获取运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。编号从1开始。 |

**退货：**
[Operator](../../com.aspose.pdf/operator) - 来自请求索引的运算符
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public abstract void insert(int index, Operator op)
```


将运算符插入集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 必须添加新运算符的索引 |
| op | [Operator](../../com.aspose.pdf/operator) | 将被插入的操作符 |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


如果集合为空，则返回 TRUE。

**退货：**
boolean - 布尔值
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```


指示集合是否仅限于快速文本提取

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


如果集合是只读的，则返回 true。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public abstract Iterator<Operator> iterator()
```


返回集合的枚举器

**退货：**
java.util.Iterator<com.aspose.pdf.Operator> - 集合枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Operator item) {#remove-com.aspose.pdf.Operator-}
```
public abstract boolean remove(Operator item)
```


从集合中移除运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | 要删除的运算符实例项。 |

**退货：**
boolean - 布尔值 True - 如果项目被移除；否则，假的。
### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


恢复文档更新。如果有任何未决更改，则更新内容流。

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public abstract void set_Item(int index, Operator value)
```


通过索引设置运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。编号从1开始。 |
| value | [Operator](../../com.aspose.pdf/operator) | 操作员。 |

### size() {#size--}
```
public abstract int size()
```


获取集合中运算符的计数。

**退货：**
int - 整数值
### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


抑制更新内容数据。在调用 ResumeUpdate 之前，内容流不会更新。

### toList() {#toList--}
```
public abstract System.Collections.Generic.List<Operator> toList()
```


返回操作者列表。

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - 运算符列表。
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updateData() {#updateData--}
```
public abstract void updateData()
```


内部的

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
