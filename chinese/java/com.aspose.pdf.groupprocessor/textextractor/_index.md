---
title: TextExtractor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示与提取器交互的实例。
type: docs
weight: 12
url: /zh/java/com.aspose.pdf.groupprocessor/textextractor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.groupprocessor.IVentureLicenseTarget

**所有已实现的接口：**
[com.aspose.pdf.groupprocessor.interfaces.IPdfTypeExtractor](../../com.aspose.pdf.groupprocessor.interfaces/ipdftypeextractor)
```
public final class TextExtractor extends IVentureLicenseTarget implements IPdfTypeExtractor
```

表示与提取器交互的实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextExtractor()](#TextExtractor--) | 创建 TextExtractor 实例。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [_numberedPages](#-numberedPages) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [buildProperties(ByteRange range, PdfTreeNode parentNode)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-) | 构建包含所有 pdf 参数及其值的节点树。 |
| [buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)](#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-) | 构建包含所有 pdf 参数及其值的节点树。 |
| [close()](#close--) | 关闭此实例使用的所有资源。 |
| [dispose()](#dispose--) | Dispose object 此方法已过时，请改用 close()。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAllText()](#extractAllText--) | 从文档中提取文本 |
| [extractAllTextInternal()](#extractAllTextInternal--) |  |
| [extractPageText(int pageNumber)](#extractPageText-int-) | 从页面中提取文本 |
| [getClass()](#getClass--) |  |
| [getPageCount()](#getPageCount--) | 获取文档中的页数。 |
| [getVentureLicense()](#getVentureLicense--) |  |
| [getVersion()](#getVersion--) | 仅供内部使用 |
| [hashCode()](#hashCode--) |  |
| [initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-int-boolean-) | 初始化 TextExtractor 实例。 |
| [initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-) | 初始化 TextExtractor 实例。 |
| [initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-int-boolean-) | 初始化 TextExtractor 实例。 |
| [initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)](#initialize-java.lang.String-java.lang.String-int-boolean-) | 初始化 TextExtractor 实例。 |
| [initializeAlternative(System.IO.Stream pdfDocumentStream)](#initializeAlternative-com.aspose.ms.System.IO.Stream-) | 初始化 TextExtractor 实例。 |
| [initializeAlternative(System.IO.Stream pdfDocumentStream, String password)](#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-) | 初始化 TextExtractor 实例。 |
| [initializeAlternative(String pdfDocumentPath)](#initializeAlternative-java.lang.String-) | 初始化 TextExtractor 实例。 |
| [initializeAlternative(String pdfDocumentPath, String password)](#initializeAlternative-java.lang.String-java.lang.String-) | 初始化 TextExtractor 实例。 |
| [isFastExtractionUsed()](#isFastExtractionUsed--) | 如果使用快速提取，则返回 TRUE |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setVentureLicense(VentureLicense license)](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextExtractor() {#TextExtractor--}
```
public TextExtractor()
```


创建 TextExtractor 实例。

### _numberedPages {#-numberedPages}
```
public final System.Collections.Generic.Dictionary<Integer,Page> _numberedPages
```


### buildProperties(ByteRange range, PdfTreeNode parentNode) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode)
```


构建包含所有 pdf 参数及其值的节点树。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | 解析参数的字节范围。 |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | 用于构建树的初始（根）节点。 |

**退货：**
long - long 值，已解析范围的最后一个索引。
### buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue) {#buildProperties-com.aspose.pdf.groupprocessor.ByteRange-com.aspose.pdf.groupprocessor.PdfTreeNode-boolean-}
```
public long buildProperties(ByteRange range, PdfTreeNode parentNode, boolean extractJustValue)
```


构建包含所有 pdf 参数及其值的节点树。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| range | com.aspose.pdf.groupprocessor.ByteRange | 解析参数的字节范围。 |
| parentNode | com.aspose.pdf.groupprocessor.PdfTreeNode | 用于构建树的初始（根）节点。 |
| extractJustValue | boolean | 用于递归调用。只是表明下一个递归函数应该找到参数值而不是参数本身。 |

**退货：**
long - 解析范围的最后一个索引。
### close() {#close--}
```
public void close()
```


关闭此实例使用的所有资源。

### dispose() {#dispose--}
```
public void dispose()
```


Dispose object 此方法已过时，请改用 close()。

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
### extractAllText() {#extractAllText--}
```
public String[] extractAllText()
```


从文档中提取文本

**退货：**
java.lang.字符串[] - 表示文档文本的字符串数组
### extractAllTextInternal() {#extractAllTextInternal--}
```
public String[] extractAllTextInternal()
```




**退货：**
java.lang.字符串[]
### extractPageText(int pageNumber) {#extractPageText-int-}
```
public String extractPageText(int pageNumber)
```


从页面中提取文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 基于 1 的页码 |

**退货：**
java.lang.String - 文本
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


获取文档中的页数。

**退货：**
int - 页数
### getVentureLicense() {#getVentureLicense--}
```
public final VentureLicense getVentureLicense()
```




**退货：**
[VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense)
### getVersion() {#getVersion--}
```
public String getVersion()
```


仅供内部使用

**退货：**
java.lang.String - 字符串对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, int bufferSize, boolean allowAsyncInitialization)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | 包含 pdf 文档的流。 |
| bufferSize | int | 可以保存在内存中的最大内容大小（以字节为单位）。 |
| allowAsyncInitialization | boolean | 允许资源的异步初始化。 |

### initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-com.aspose.ms.System.IO.Stream-java.lang.String-int-boolean-}
```
public void initialize(System.IO.Stream pdfDocumentStream, String password, int bufferSize, boolean allowAsyncInitialization)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | 包含 pdf 文档的流。 |
| password | java.lang.String | 文档密码。 |
| bufferSize | int | 可以保存在内存中的最大内容大小（以字节为单位）。 |
| allowAsyncInitialization | boolean | 允许资源的异步初始化。 |

### initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, int bufferSize, boolean allowAsyncInitialization)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | pdf 文档的路径。 |
| bufferSize | int | 可以保存在内存中的最大内容大小（以字节为单位）。 |
| allowAsyncInitialization | boolean | 允许资源的异步初始化。 |

### initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization) {#initialize-java.lang.String-java.lang.String-int-boolean-}
```
public void initialize(String pdfDocumentPath, String password, int bufferSize, boolean allowAsyncInitialization)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | pdf 文档的路径。 |
| password | java.lang.String | 文档密码。 |
| bufferSize | int | 可以保存在内存中的最大内容大小（以字节为单位）。 |
| allowAsyncInitialization | boolean | 允许资源的异步初始化。 |

### initializeAlternative(System.IO.Stream pdfDocumentStream) {#initializeAlternative-com.aspose.ms.System.IO.Stream-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | 包含 pdf 文档的流。 |

### initializeAlternative(System.IO.Stream pdfDocumentStream, String password) {#initializeAlternative-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public void initializeAlternative(System.IO.Stream pdfDocumentStream, String password)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentStream | com.aspose.ms.System.IO.Stream | 包含 pdf 文档的流。 |
| password | java.lang.String |  |

### initializeAlternative(String pdfDocumentPath) {#initializeAlternative-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | pdf 文档的路径。 |

### initializeAlternative(String pdfDocumentPath, String password) {#initializeAlternative-java.lang.String-java.lang.String-}
```
public void initializeAlternative(String pdfDocumentPath, String password)
```


初始化 TextExtractor 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfDocumentPath | java.lang.String | pdf 文档的路径。 |
| password | java.lang.String |  |

### isFastExtractionUsed() {#isFastExtractionUsed--}
```
public boolean isFastExtractionUsed()
```


如果使用快速提取，则返回 TRUE

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




### setVentureLicense(VentureLicense license) {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
```
public final void setVentureLicense(VentureLicense license)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| license | [VentureLicense](../../com.aspose.pdf.engine.licensemanagement/venturelicense) |  |

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
