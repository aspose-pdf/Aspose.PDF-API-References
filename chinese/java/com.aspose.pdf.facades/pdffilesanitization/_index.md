---
title: PdfFileSanitization
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示清理和恢复 API。
type: docs
weight: 43
url: /zh/java/com.aspose.pdf.facades/pdffilesanitization/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**所有已实现的接口：**
[com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery](../../com.aspose.pdf.engine.security.impl.signatures.sanitization/irecovery)
```
public final class PdfFileSanitization extends SaveableFacade implements IRecovery
```

表示清理和恢复 API。如果您无法以任何其他方式创建/打开文档，请使用它。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSanitization()](#PdfFileSanitization--) | 初始化一个新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(Document srcDoc)](#bindPdf-com.aspose.pdf.Document-) | 初始化门面。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | 为 Sanitize 绑定一个 Pdf 流。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | 为 Sanitize 绑定一个 Pdf 文件。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭门面。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getLog()](#getLog--) | 文件保存后，您可以检查对文件做了什么。 |
| [getUseRebuildXrefAndTrailer()](#getUseRebuildXrefAndTrailer--) | 允许为文档生成新的外部参照和预告片。 |
| [getUseTrimBottom()](#getUseTrimBottom--) | 允许删除 pdf 数据后的数据 |
| [getUseTrimTop()](#getUseTrimTop--) | 允许删除 pdf 数据之前的数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rebuildXrefAndTrailer()](#rebuildXrefAndTrailer--) | 删除带尾部的旧外部参照并创建带尾部的新外部参照。 |
| [recover()](#recover--) | 恢复文档。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 将结果 PDF 保存到流中。 |
| [save(String outputFile)](#save-java.lang.String-) | 将结果 PDF 保存到文件。 |
| [setUseRebuildXrefAndTrailer(boolean value)](#setUseRebuildXrefAndTrailer-boolean-) | 允许为文档生成新的外部参照和预告片。 |
| [setUseTrimBottom(boolean value)](#setUseTrimBottom-boolean-) | 允许删除 pdf 数据后的数据 |
| [setUseTrimTop(boolean value)](#setUseTrimTop-boolean-) | 允许删除 pdf 数据之前的数据。 |
| [toString()](#toString--) |  |
| [trimBottom()](#trimBottom--) | 删除最后 %%EOF 之后的数据。 |
| [trimTop()](#trimTop--) | 删除 %PDF 之前的数据。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSanitization() {#PdfFileSanitization--}
```
public PdfFileSanitization()
```


初始化一个新实例。

### bindPdf(Document srcDoc) {#bindPdf-com.aspose.pdf.Document-}
```
public void bindPdf(Document srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [Document](../../com.aspose.pdf/document) | 文档对象。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


为 Sanitize 绑定一个 Pdf 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要编辑的 pdf 流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


为 Sanitize 绑定一个 Pdf 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 要编辑的 pdf 文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


关闭门面。

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

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
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getLog() {#getLog--}
```
public final List<String> getLog()
```


文件保存后，您可以检查对文件做了什么。

**退货：**
java.util.List<java.lang.String> - 字符串元素列表
### getUseRebuildXrefAndTrailer() {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```


允许为文档生成新的外部参照和预告片。

**退货：**
boolean - 布尔值
### getUseTrimBottom() {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```


允许删除 pdf 数据后的数据

**退货：**
boolean - 布尔值
### getUseTrimTop() {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```


允许删除 pdf 数据之前的数据。

**退货：**
boolean - 布尔值
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




### rebuildXrefAndTrailer() {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```


删除带尾部的旧外部参照并创建带尾部的新外部参照。

### recover() {#recover--}
```
public final void recover()
```


恢复文档。使用属性进行自定义。

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


将结果 PDF 保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出pdf流 |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


将结果 PDF 保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 输出pdf文件 |

### setUseRebuildXrefAndTrailer(boolean value) {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```


允许为文档生成新的外部参照和预告片。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUseTrimBottom(boolean value) {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```


允许删除 pdf 数据后的数据

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUseTrimTop(boolean value) {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```


允许删除 pdf 数据之前的数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### trimBottom() {#trimBottom--}
```
public final void trimBottom()
```


删除最后 %%EOF 之后的数据。

### trimTop() {#trimTop--}
```
public final void trimTop()
```


删除 %PDF 之前的数据。

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
