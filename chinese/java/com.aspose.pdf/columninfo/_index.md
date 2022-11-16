---
title: ColumnInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示列信息。
type: docs
weight: 67
url: /zh/java/com.aspose.pdf/columninfo/
---
**遗产：**
java.lang.Object
```
public final class ColumnInfo
```

此类表示列信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColumnInfo()](#ColumnInfo--) | 初始化 ColumnInfo 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | 获取指示列数的 int 值。 |
| [getColumnSpacing()](#getColumnSpacing--) | 获取或设置包含列间距的字符串。 |
| [getColumnWidths()](#getColumnWidths--) | 获取或设置包含列宽的字符串。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColumnCount(int value)](#setColumnCount-int-) | 设置指示列数的 int 值。 |
| [setColumnSpacing(String value)](#setColumnSpacing-java.lang.String-) | 获取或设置包含列间距的字符串。 |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | 获取或设置包含列宽的字符串。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColumnInfo() {#ColumnInfo--}
```
public ColumnInfo()
```


初始化 ColumnInfo 类的新实例。

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
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


获取指示列数的 int 值。

**退货：**
int - 列数
### getColumnSpacing() {#getColumnSpacing--}
```
public String getColumnSpacing()
```


获取或设置包含列间距的字符串。每个间距的值应该用空格分隔。默认单位为点，但也支持厘米和英寸。例如，“120 2.5cm 1.5inch”。

--------------------

如果未设置此属性，则每个间距将使用默认值 0。

**退货：**
java.lang.String - 字符串值
### getColumnWidths() {#getColumnWidths--}
```
public String getColumnWidths()
```


获取或设置包含列宽的字符串。每列的值应该用空格分隔。默认单位是点，但也支持厘米、英寸和可用宽度的百分比。例如，“120 2.5cm 1.5inch”

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


设置指示列数的 int 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 列数 |

### setColumnSpacing(String value) {#setColumnSpacing-java.lang.String-}
```
public void setColumnSpacing(String value)
```


获取或设置包含列间距的字符串。每个间距的值应该用空格分隔。默认单位为点，但也支持厘米和英寸。例如，“120 2.5cm 1.5inch”。

--------------------

如果未设置此属性，则每个间距将使用默认值 0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public void setColumnWidths(String value)
```


获取或设置包含列宽的字符串。每列的值应该用空格分隔。默认单位是点，但也支持厘米、英寸和可用宽度的百分比。例如，“120 2.5cm 1.5inch”

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

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
