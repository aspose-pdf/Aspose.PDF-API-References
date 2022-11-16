---
title: INamedDestinationCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 命名目的地的集合。
type: docs
weight: 11
url: /zh/java/com.aspose.pdf.nameddestinations/inameddestinationcollection/
---
```
public interface INamedDestinationCollection
```

命名目的地的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | 添加新的命名目的地。 |
| [getNames()](#getNames--) | 获取目的地名称数组。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过名称获取目的地。 |
| [remove(String name)](#remove-java.lang.String-) | 按名称删除目的地。 |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | 按名称设置目的地。 |
| [size()](#size--) | 返回目的地的计数。 |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void add(String name, IAppointment appointment)
```


添加新的命名目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment 实例 |

### getNames() {#getNames--}
```
public abstract String[] getNames()
```


获取目的地名称数组。

**退货：**
java.lang.字符串[- 字符串值数组
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract IAppointment get_Item(String name)
```


通过名称获取目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment) IAppointment 实例目标对象。
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


按名称删除目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void set_Item(String name, IAppointment value)
```


按名称设置目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment 实例 Destination 对象。 |

### size() {#size--}
```
public abstract int size()
```


返回目的地的计数。

**退货：**
int - 整数值