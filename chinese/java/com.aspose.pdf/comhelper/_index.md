---
title: ComHelper
second_title: 用于 Java API 参考的 Aspose.PDF
description: 为 COM 客户端提供将文档加载到 Aspose.PDF 的方法。
type: docs
weight: 68
url: /zh/java/com.aspose.pdf/comhelper/
---
**遗产：**
java.lang.Object
```
public class ComHelper
```

为 COM 客户端提供将文档加载到 Aspose.PDF 的方法。

--------------------

使用 ComHelper 类将文件或流中的文档加载到 COM 应用程序中的 Document 对象中。 Document 类提供默认构造函数来创建新文档，还提供重载构造函数来从文件或流加载文档。如果您在 .NET 应用程序中使用 Aspose.Words，则可以直接使用所有文档构造函数，但如果您在 COM 应用程序中使用 Aspose.PDF，则只有默认的文档构造函数可用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComHelper()](#ComHelper--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFile(String filename)](#openFile-java.lang.String-) | 只需使用 filename 创建并返回 Document 。 |
| [openFile(String filename, LoadOptions options)](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | 从提供必要的转换选项的文件中打开现有文档以获取 pdf 文档。 |
| [openFile(String filename, String password)](#openFile-java.lang.String-java.lang.String-) | 初始化并返回用于处理加密文档的 Document 类的新实例。 |
| [openFile(String filename, String password, boolean isManagedStream)](#openFile-java.lang.String-java.lang.String-boolean-) | 初始化 Document 类的新实例以处理加密文档。 |
| [openStream(InputStream input)](#openStream-java.io.InputStream-) | 从输入流初始化并返回新的 Document 实例。 |
| [openStream(InputStream input, boolean isManagedStream)](#openStream-java.io.InputStream-boolean-) | 从输入流初始化并返回新的 Document 实例。 |
| [openStream(InputStream input, LoadOptions options)](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 从提供必要转换以获取 pdf 文档的流中打开并返回现有文档。 |
| [openStream(InputStream input, String password)](#openStream-java.io.InputStream-java.lang.String-) | 从输入流初始化并返回新的 Document 实例。 |
| [openStream(InputStream input, String password, boolean isManagedStream)](#openStream-java.io.InputStream-java.lang.String-boolean-) | 从输入流初始化并返回新的 Document 实例。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComHelper() {#ComHelper--}
```
public ComHelper()
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




### openFile(String filename) {#openFile-java.lang.String-}
```
public Document openFile(String filename)
```


只需使用 filename 创建并返回 Document 。与 Document(Stream) 相同。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | pdf 文档文件的名称。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openFile(String filename, LoadOptions options) {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public Document openFile(String filename, LoadOptions options)
```


从提供必要的转换选项的文件中打开现有文档以获取 pdf 文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 要转换为 pdf 文档的输入文件。 |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | 表示将文件名转换为 pdf 文档的属性。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openFile(String filename, String password) {#openFile-java.lang.String-java.lang.String-}
```
public Document openFile(String filename, String password)
```


初始化并返回用于处理加密文档的 Document 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 文档文件名。 |
| password | java.lang.String | 用户或所有者密码。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openFile(String filename, String password, boolean isManagedStream) {#openFile-java.lang.String-java.lang.String-boolean-}
```
public Document openFile(String filename, String password, boolean isManagedStream)
```


初始化 Document 类的新实例以处理加密文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 文档文件名。 |
| password | java.lang.String | 用户或所有者密码。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openStream(InputStream input) {#openStream-java.io.InputStream-}
```
public Document openStream(InputStream input)
```


从输入流初始化并返回新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openStream(InputStream input, boolean isManagedStream) {#openStream-java.io.InputStream-boolean-}
```
public Document openStream(InputStream input, boolean isManagedStream)
```


从输入流初始化并返回新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openStream(InputStream input, LoadOptions options) {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document openStream(InputStream input, LoadOptions options)
```


从提供必要转换以获取 pdf 文档的流中打开并返回现有文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 要转换为 pdf 文档的输入流。 |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | 表示将输入转换为 pdf 文档的属性。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openStream(InputStream input, String password) {#openStream-java.io.InputStream-java.lang.String-}
```
public Document openStream(InputStream input, String password)
```


从输入流初始化并返回新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 输入流对象，对应的pdf受密码保护。 |
| password | java.lang.String | 用户或所有者密码。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
### openStream(InputStream input, String password, boolean isManagedStream) {#openStream-java.io.InputStream-java.lang.String-boolean-}
```
public Document openStream(InputStream input, String password, boolean isManagedStream)
```


从输入流初始化并返回新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |
| password | java.lang.String | 用户或所有者密码。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

**退货：**
[Document](../../com.aspose.pdf/document) - 文档对象
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
