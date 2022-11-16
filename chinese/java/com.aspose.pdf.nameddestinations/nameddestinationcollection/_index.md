---
title: NamedDestinationCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示所有目的地的集合，名称树将名称字符串映射到目的地，请参阅 pdf 文档中的 12.3.2.3 命名目的地和 7.7.4 名称字典。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.nameddestinations/nameddestinationcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.pdf.nameddestinations.INamedDestinationCollection](../../com.aspose.pdf.nameddestinations/inameddestinationcollection)
```
public class NamedDestinationCollection implements INamedDestinationCollection
```

类表示 pdf 文档中所有目的地的集合（名称树将名称字符串映射到目的地（参见 12.3.2.3，“命名目的地”）和（参见 7.7.4，“名称字典”））。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | 添加新的命名目的地。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | 目的地名称列表。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 按名称获取或设置约会。 |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String name)](#remove-java.lang.String-) | 删除命名目的地。 |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | 按名称获取或设置约会。 |
| [size()](#size--) | 命名目的地的计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void add(String name, IAppointment appointment)
```


添加新的命名目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 目的地名称。 |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | 约会添加。 |

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
### getNames() {#getNames--}
```
public String[] getNames()
```


目的地名称列表。

**退货：**
java.lang.字符串[]
### get_Item(String name) {#get-Item-java.lang.String-}
```
public IAppointment get_Item(String name)
```


按名称获取或设置约会。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 约会的名称。 |

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment) - 预约
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




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




### remove(String name) {#remove-java.lang.String-}
```
public void remove(String name)
```


删除命名目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的目的地的名称。 |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void set_Item(String name, IAppointment value)
```


按名称获取或设置约会。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 约会的名称。 |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 约会实例 |

### size() {#size--}
```
public int size()
```


命名目的地的计数。

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
