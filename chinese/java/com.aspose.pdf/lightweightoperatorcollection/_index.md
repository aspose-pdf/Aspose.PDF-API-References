---
title: LightweightOperatorCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 轻量级运算符集合。
type: docs
weight: 194
url: /zh/java/com.aspose.pdf/lightweightoperatorcollection/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

轻量级运算符集合。旨在用于未附加底层内容流的场景，结果只需要运算符集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LightweightOperatorCollection()](#LightweightOperatorCollection--) | 初始化对象 |
| [LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | 仅供内部使用！ |
| [LightweightOperatorCollection(OperatorCollection operatorCollection)](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | 初始化对象 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | 添加运营商 |
| [addRange(LightweightOperatorCollection oc)](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | 添加 LightweightOperatorCollection |
| [cancelUpdate()](#cancelUpdate--) | 取消上次更新。 |
| [clear()](#clear--) |  |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) |  |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | 内部删除 Unrestrictedelement |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | 供内部使用 getUnrestricted 运算符 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取运算符。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | 插入运算符 |
| [isEmpty()](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | 指示集合是否仅限于快速文本提取 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [iterator()](#iterator--) | 返回迭代器 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) |  |
| [resumeUpdate()](#resumeUpdate--) | 恢复文档更新。 |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | 通过索引设置运算符。 |
| [size()](#size--) | 运算符计数 |
| [suppressUpdate()](#suppressUpdate--) | 抑制更新内容数据。 |
| [toList()](#toList--) | 返回运算符列表。 |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | 内部的 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LightweightOperatorCollection() {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```


初始化对象

### LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators) {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)
```


仅供内部使用！

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | 内部对象 |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> | 内部对象 |

### LightweightOperatorCollection(OperatorCollection operatorCollection) {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
```
public LightweightOperatorCollection(OperatorCollection operatorCollection)
```


初始化对象

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operatorCollection | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection 对象 |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


添加运营商

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

### addRange(LightweightOperatorCollection oc) {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
```
public void addRange(LightweightOperatorCollection oc)
```


添加 LightweightOperatorCollection

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| oc | [LightweightOperatorCollection](../../com.aspose.pdf/lightweightoperatorcollection) | LightweightOperatorCollection 实例 |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


取消上次更新。当更改不应该引发内容更新时，可以调用此方法。

### clear() {#clear--}
```
public void clear()
```


清除集合。

### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator item)
```


检查该项目是否在收藏中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | 算子实例 |

**退货：**
boolean - 布尔值
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


内部删除 Unrestrictedelement

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
public Operator getUnrestricted(int index)
```


供内部使用 getUnrestricted 运算符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |

**退货：**
[Operator](../../com.aspose.pdf/operator) - 操作员对象
### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


通过其索引获取运算符。

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

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
public void insert(int index, Operator op)
```


插入运算符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |
| op | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


如果集合为空，则返回 TRUE。

**退货：**
boolean - 布尔值
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


指示集合是否仅限于快速文本提取

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
布尔值
### iterator() {#iterator--}
```
public Iterator<Operator> iterator()
```


返回迭代器

**退货：**
java.util.Iterator<com.aspose.pdf.Operator> - IGenericEnumerator 对象
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
public boolean remove(Operator item)
```


从集合中移除运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | 算子实例 |

**退货：**
boolean - 布尔值
### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


恢复文档更新。如果有任何未决更改，则更新内容流。

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


通过索引设置运算符。

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。编号从1开始。 |
| value | [Operator](../../com.aspose.pdf/operator) | 来自请求索引的运算符 |

### size() {#size--}
```
public int size()
```


运算符计数

**退货：**
int - 整数值
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


抑制更新内容数据。在调用 ResumeUpdate 之前，内容流不会更新。

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


返回运算符列表。

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
public void updateData()
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
