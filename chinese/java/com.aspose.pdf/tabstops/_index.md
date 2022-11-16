---
title: TabStops
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 TabStop 对象的集合。
type: docs
weight: 351
url: /zh/java/com.aspose.pdf/tabstops/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.ICloneable
```
public class TabStops implements System.ICloneable
```

表示 TabStop 对象的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TabStops()](#TabStops--) | 初始化 TabStops 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add()](#add--) | 初始化 TabStop 类的新实例并将其添加到 TabStops 集合。 |
| [add(TabStop tabStop)](#add-com.aspose.pdf.TabStop-) | 将 TabStop 类的实例添加到 TabStops 集合。 |
| [add(float position)](#add-float-) | 初始化具有指定位置的 TabStop 类的新实例，并将其添加到 TabStops 集合。 |
| [add(float position, int leaderType)](#add-float-int-) | 使用指定的位置和前导符类型初始化 TabStop 类的新实例，并将其添加到 TabStops 集合。 |
| [deepClone()](#deepClone--) | 克隆一个新的 TabStops 对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 返回 tabStops Cound |
| [get_Item(int index)](#get-Item-int-) | 根据 TabStop 索引从集合中获取一个 TabStop 对象。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取指示此 TabStops 实例已附加到 TextFragment 并变为只读的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set_Item(int index, TabStop value)](#set-Item-int-com.aspose.pdf.TabStop-) | 根据 TabStop 索引从集合中设置一个 TabStop 对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TabStops() {#TabStops--}
```
public TabStops()
```


初始化 TabStops 类的新实例。

### add() {#add--}
```
public TabStop add()
```


初始化 TabStop 类的新实例并将其添加到 TabStops 集合。

**退货：**
[TabStop](../../com.aspose.pdf/tabstop) - 新的 TabStop 对象。
### add(TabStop tabStop) {#add-com.aspose.pdf.TabStop-}
```
public void add(TabStop tabStop)
```


将 TabStop 类的实例添加到 TabStops 集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tabStop | [TabStop](../../com.aspose.pdf/tabstop) | TabStop 对象。 |

### add(float position) {#add-float-}
```
public TabStop add(float position)
```


初始化具有指定位置的 TabStop 类的新实例，并将其添加到 TabStops 集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 制表位的位置。 |

**退货：**
[TabStop](../../com.aspose.pdf/tabstop) - 新的 TabStop 对象。
### add(float position, int leaderType) {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```


使用指定的位置和前导符类型初始化 TabStop 类的新实例，并将其添加到 TabStops 集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 制表位的位置。 |
| leaderType | int | 制表位的前导符类型。 |

**退货：**
[TabStop](../../com.aspose.pdf/tabstop) - 新的 TabStop 对象。
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆一个新的 TabStops 对象。

**退货：**
java.lang.Object - 新的 TabStops 对象。
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


返回 tabStops Cound

**退货：**
int - 整数值
### get_Item(int index) {#get-Item-int-}
```
public TabStop get_Item(int index)
```


根据 TabStop 索引从集合中获取一个 TabStop 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | TabStops 集合中元素的从零开始的索引。 |

**退货：**
[TabStop](../../com.aspose.pdf/tabstop) - TabStop 对象。
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


获取指示此 TabStops 实例已附加到 TextFragment 并变为只读的值。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set_Item(int index, TabStop value) {#set-Item-int-com.aspose.pdf.TabStop-}
```
public void set_Item(int index, TabStop value)
```


根据 TabStop 索引从集合中设置一个 TabStop 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | TabStops 集合中元素的从零开始的索引。 |
| value | [TabStop](../../com.aspose.pdf/tabstop) |  制表位对象。 |

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
