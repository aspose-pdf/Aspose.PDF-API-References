---
title: FileParams
second_title: 用于 Java API 参考的 Aspose.PDF
description: 定义一个嵌入式文件参数字典，其中应包含附加的文件特定信息。
type: docs
weight: 116
url: /zh/java/com.aspose.pdf/fileparams/
---
**遗产：**
java.lang.Object
```
public final class FileParams
```

定义一个嵌入式文件参数字典，其中应包含附加的文件特定信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileParams(FileSpecification spec)](#FileParams-com.aspose.pdf.FileSpecification-) | FileParams 类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckSum()](#getCheckSum--) | 一个 16 字节的字符串，它是未压缩的嵌入文件的字节校验和。 |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | 获取创建嵌入文件的日期和时间。 |
| [getModDate()](#getModDate--) | 获取上次修改嵌入文件的日期和时间。 |
| [getSize()](#getSize--) | 未压缩的嵌入文件的大小，以字节为单位。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | 设置嵌入文件的创建日期和时间。 |
| [setModDate(Date value)](#setModDate-java.util.Date-) | 设置嵌入文件上次修改的日期和时间。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileParams(FileSpecification spec) {#FileParams-com.aspose.pdf.FileSpecification-}
```
public FileParams(FileSpecification spec)
```


FileParams 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| spec | [FileSpecification](../../com.aspose.pdf/filespecification) | 文件规范。 |

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
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


一个 16 字节的字符串，它是未压缩的嵌入文件的字节校验和。校验和是通过将标准 MD5 消息摘要算法应用于嵌入式文件流的字节来计算的。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


获取创建嵌入文件的日期和时间。

**退货：**
[Date](../../java.util/date) - 日期对象
### getModDate() {#getModDate--}
```
public Date getModDate()
```


获取上次修改嵌入文件的日期和时间。

**退货：**
[Date](../../java.util/date) - 日期对象
### getSize() {#getSize--}
```
public int getSize()
```


未压缩的嵌入文件的大小，以字节为单位。

**退货：**
int - 整数值
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




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


设置嵌入文件的创建日期和时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


设置嵌入文件上次修改的日期和时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

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
