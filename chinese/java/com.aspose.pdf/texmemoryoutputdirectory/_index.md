---
title: TeXMemoryOutputDirectory
second_title: 用于 Java API 参考的 Aspose.PDF
description: 实现从内存中获取输出流。
type: docs
weight: 358
url: /zh/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.tex.ITeXOutputDirectory 目录
```
public class TeXMemoryOutputDirectory implements ITeXOutputDirectory
```

实现从内存中获取输出流。例如，当您不想将伴随的输出（如日志文件）写入磁盘但您希望事后从内存中读取它时，您可以使用它。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeXMemoryOutputDirectory()](#TeXMemoryOutputDirectory--) | 创建新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 处置实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile(String fileName, String[] fullName)](#getFile-java.lang.String-java.lang.String---) | 返回要读取的流。 |
| [getFile(String fileName, String[] fullName, boolean searchSubdirectories)](#getFile-java.lang.String-java.lang.String---boolean-) | 返回要读取的流。 |
| [getOutputFile(String fileName, String[] fullName)](#getOutputFile-java.lang.String-java.lang.String---) | 返回要写入的流。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXMemoryOutputDirectory() {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```


创建新实例。

### close() {#close--}
```
public void close()
```


处置实例。

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
### getFile(String fileName, String[] fullName) {#getFile-java.lang.String-java.lang.String---}
```
public final InputStream getFile(String fileName, String[] fullName)
```


返回要读取的流。

无需在子目录中查找文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| fullName | java.lang.String[] | 完整的文件名。在这个实现中没有效果。 |

**退货：**
java.io.InputStream - 流。
### getFile(String fileName, String[] fullName, boolean searchSubdirectories) {#getFile-java.lang.String-java.lang.String---boolean-}
```
public InputStream getFile(String fileName, String[] fullName, boolean searchSubdirectories)
```


返回要读取的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| fullName | java.lang.String[] | 完整的文件名。 |
| searchSubdirectories | boolean | 指示是否在子目录中查找文件。在这个实现中没有效果。 |

**退货：**
java.io.InputStream - 流。
### getOutputFile(String fileName, String[] fullName) {#getOutputFile-java.lang.String-java.lang.String---}
```
public OutputStream getOutputFile(String fileName, String[] fullName)
```


返回要写入的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 字符串值 文件名。 |
| fullName | java.lang.String[] | 数组中的字符串值 完整的文件名。 |

**退货：**
java.io.OutputStream - OutputStream 实例
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
