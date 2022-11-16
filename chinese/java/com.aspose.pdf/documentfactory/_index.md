---
title: DocumentFactory
second_title: 用于 Java API 参考的 Aspose.PDF
description: 允许创建/加载不同类型文档的类。
type: docs
weight: 93
url: /zh/java/com.aspose.pdf/documentfactory/
---
**遗产：**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget
```
public class DocumentFactory extends IVentureLicenseTarget
```

允许创建/加载不同类型文档的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentFactory()](#DocumentFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDocument()](#createDocument--) | 创建空文档。 |
| [createDocument(InputStream input)](#createDocument-java.io.InputStream-) | 从流中加载文档。 |
| [createDocument(InputStream input, LoadOptions options)](#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 创建文档。 |
| [createDocument(InputStream input, String password)](#createDocument-java.io.InputStream-java.lang.String-) | 从流中加载受密码保护的文档。 |
| [createDocument(String fileName)](#createDocument-java.lang.String-) | 从文件加载文档。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentFactory() {#DocumentFactory--}
```
public DocumentFactory()
```


### createDocument() {#createDocument--}
```
public Document createDocument()
```


创建空文档。

**退货：**
[Document](../../com.aspose.pdf/document) - 创建的文档。
### createDocument(InputStream input) {#createDocument-java.io.InputStream-}
```
public Document createDocument(InputStream input)
```


从流中加载文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 输入流。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 创建的文档。
### createDocument(InputStream input, LoadOptions options) {#createDocument-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document createDocument(InputStream input, LoadOptions options)
```


创建文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 输入流。 |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | 文档加载选项。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### createDocument(InputStream input, String password) {#createDocument-java.io.InputStream-java.lang.String-}
```
public Document createDocument(InputStream input, String password)
```


从流中加载受密码保护的文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 源码流。 |
| password | java.lang.String | 用于访问文档的密码。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 创建的文档。
### createDocument(String fileName) {#createDocument-java.lang.String-}
```
public Document createDocument(String fileName)
```


从文件加载文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | PDF 文件的名称。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 创建的文档。
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
