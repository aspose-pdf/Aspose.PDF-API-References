---
title: PdfJavaScriptStripper
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于删除所有 Java Script 代码的类。
type: docs
weight: 48
url: /zh/java/com.aspose.pdf.facades/pdfjavascriptstripper/
---
**遗产：**
java.lang.Object
```
public final class PdfJavaScriptStripper
```

用于删除所有 Java Script 代码的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfJavaScriptStripper()](#PdfJavaScriptStripper--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strip(InputStream inStream, OutputStream outStream)](#strip-java.io.InputStream-java.io.OutputStream-) | 从文档中删除 Java Script。 |
| [strip(String inputFile, String outputFile)](#strip-java.lang.String-java.lang.String-) | 从文档中删除 Java 脚本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfJavaScriptStripper() {#PdfJavaScriptStripper--}
```
public PdfJavaScriptStripper()
```


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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strip(InputStream inStream, OutputStream outStream) {#strip-java.io.InputStream-java.io.OutputStream-}
```
public boolean strip(InputStream inStream, OutputStream outStream)
```


从文档中删除 Java Script。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inStream | java.io.InputStream | 包含文档的流。 |
| outStream | java.io.OutputStream | 将存储文档的流。 |

**退货：**
boolean - 如果 JavaScript 被成功剥离则为 true。
### strip(String inputFile, String outputFile) {#strip-java.lang.String-java.lang.String-}
```
public boolean strip(String inputFile, String outputFile)
```


从文档中删除 Java 脚本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 包含文档的文件。 |
| outputFile | java.lang.String | 将存储文档的文件。 |

**退货：**
boolean - 如果 JavaScript 被成功剥离则为 true。
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
