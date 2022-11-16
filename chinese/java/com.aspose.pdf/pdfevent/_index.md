---
title: PdfEvent
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示事件的类
type: docs
weight: 277
url: /zh/java/com.aspose.pdf/pdfevent/
---
**遗产：**
java.lang.Object
```
public abstract class PdfEvent<T>
```

表示事件的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfEvent()](#PdfEvent--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(T delegate)](#add-T-) | 再增加一名代表。 |
| [assign(T delegate)](#assign-T-) | 仅添加当前委托，清除其他委托。 |
| [clear()](#clear--) | 清空代表名单 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | 如果处理程序列表为空，则返回 true |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(T delegate)](#remove-T-) | 从列表中删除代表 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEvent() {#PdfEvent--}
```
public PdfEvent()
```


### add(T delegate) {#add-T-}
```
public final void add(T delegate)
```


再增加一名代表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| delegate | T | 处理程序对象 |

### assign(T delegate) {#assign-T-}
```
public final void assign(T delegate)
```


仅添加当前委托，清除其他委托。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| delegate | T | 处理程序对象 |

### clear() {#clear--}
```
public final void clear()
```


清空代表名单

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


如果处理程序列表为空，则返回 true

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




### remove(T delegate) {#remove-T-}
```
public final void remove(T delegate)
```


从列表中删除代表

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| delegate | T | 处理程序对象 |

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
