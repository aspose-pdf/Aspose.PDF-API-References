---
title: Cells
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示行的单元格集合。
type: docs
weight: 53
url: /zh/java/com.aspose.pdf/cells/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class Cells implements Iterable<Cell>
```

表示行的单元格集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Cells()](#Cells--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add()](#add--) | 将单元格添加到集合中。 |
| [add(Cell cell)](#add-com.aspose.pdf.Cell-) | 将单元格添加到集合中。 |
| [add(String text)](#add-java.lang.String-) | 将单元格添加到集合中。 |
| [add(String text, TextState ts)](#add-java.lang.String-com.aspose.pdf.TextState-) | 将单元格添加到集合中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 物品很重要。 |
| [get_Item(int index)](#get-Item-int-) | 获取单元格。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Cell cell)](#insert-int-com.aspose.pdf.Cell-) | 将单元格插入集合。 |
| [iterator()](#iterator--) | 获取集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Cell cell)](#remove-com.aspose.pdf.Cell-) | 从集合中删除单元格集。 |
| [remove(Object obj)](#remove-java.lang.Object-) | 从集合中删除单元格集。 |
| [removeRange(int index, int count)](#removeRange-int-int-) | 从集合中删除单元格集。 |
| [set_Item(int index, Cell value)](#set-Item-int-com.aspose.pdf.Cell-) | 设置单元格。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cells() {#Cells--}
```
public Cells()
```


### add() {#add--}
```
public Cell add()
```


将单元格添加到集合中。

**退货：**
[Cell](../../com.aspose.pdf/cell) - 新细胞
### add(Cell cell) {#add-com.aspose.pdf.Cell-}
```
public void add(Cell cell)
```


将单元格添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cell | [Cell](../../com.aspose.pdf/cell) | 要收集的单元格。 |

### add(String text) {#add-java.lang.String-}
```
public Cell add(String text)
```


将单元格添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 单元格的文本。 |

**退货：**
[Cell](../../com.aspose.pdf/cell) - 新细胞
### add(String text, TextState ts) {#add-java.lang.String-com.aspose.pdf.TextState-}
```
public Cell add(String text, TextState ts)
```


将单元格添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 单元格的文本。 |
| ts | [TextState](../../com.aspose.pdf/textstate) | 文本状态。 |

**退货：**
[Cell](../../com.aspose.pdf/cell) - 新细胞
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
### getCount() {#getCount--}
```
public int getCount()
```


物品很重要。

**退货：**
int - 整数值
### get_Item(int index) {#get-Item-int-}
```
public Cell get_Item(int index)
```


获取单元格。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 细胞指数。 |

**退货：**
[Cell](../../com.aspose.pdf/cell) 细胞对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(int index, Cell cell) {#insert-int-com.aspose.pdf.Cell-}
```
public void insert(int index, Cell cell)
```


将单元格插入集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 选定的索引。 |
| cell | [Cell](../../com.aspose.pdf/cell) | 选定的单元格。 |

### iterator() {#iterator--}
```
public Iterator<Cell> iterator()
```


获取集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.Cell> - Cell 实例的迭代器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Cell cell) {#remove-com.aspose.pdf.Cell-}
```
public void remove(Cell cell)
```


从集合中删除单元格集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cell | [Cell](../../com.aspose.pdf/cell) | 单元格对象。 |

### remove(Object obj) {#remove-java.lang.Object-}
```
public void remove(Object obj)
```


从集合中删除单元格集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 物体。 |

### removeRange(int index, int count) {#removeRange-int-int-}
```
public void removeRange(int index, int count)
```


从集合中删除单元格集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合索引。 |
| count | int | 行计数。 |

### set_Item(int index, Cell value) {#set-Item-int-com.aspose.pdf.Cell-}
```
public void set_Item(int index, Cell value)
```


设置单元格。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 细胞指数。 |
| value | [Cell](../../com.aspose.pdf/cell) | 单元格值 |

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
