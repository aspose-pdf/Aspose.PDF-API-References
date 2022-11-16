---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 如果 HtmlSaveOptions 的 SplitToPages 属性，则在将 PDF 转换为 HTML 期间，会为每个转换后的页面创建多个 HTML 文件一个 HTML 文件。
type: docs
weight: 20
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**遗产：**
java.lang.Object
```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo
```

如果 HtmlSaveOptions 的 SplitToPages 属性，则在将 PDF 转换为 HTML 期间会创建多个 HTML 文件（每个转换后的页面一个 HTML 文件）。此类表示与在将 PDF 转换为 HTML 期间自定义保存一个 HTML 页面标记相关的一组数据
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | 由转换器设置。 |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | 由转换器设置。 |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | 由转换器设置。 |
| [getSupposedFileName()](#getSupposedFileName--) | 由转换器设置。 |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | 必要时应在自定义代码中设置。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContentStream(InputStream contentStream)](#setContentStream-java.io.InputStream-) | 由转换器设置。 |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | 必要时应在自定义代码中设置。 |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | 由转换器设置。 |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | 由转换器设置。 |
| [setSupposedFileName(String supposedFileName)](#setSupposedFileName-java.lang.String-) | 由转换器设置。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getContentStream() {#getContentStream--}
```
public InputStream getContentStream()
```


由转换器设置。表示保存为流的 HTML

**退货：**
java.io.InputStream - InputStream 实例
### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


由转换器设置。如果设置 SplitToPages 属性，则在创建转换期间创建多个 HTML 文件（每个转换页面一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可用于自定义代码的逻辑，以决定如何处理或在何处保存 HTML 页面，如果关闭页面拆分，则此值始终包含“1”，因为在这种情况下，整个源文档只会生成一个大的 HTML 页面.

**退货：**
int - 整数值
### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


由转换器设置。如果设置了 SplitToPages 属性，则在创建转换期间会创建多个 HTML 文件（每个转换后的页面一个 HTML 文件）。此属性告诉自定义代码从原始 PDF 的哪一页创建保存的 HTML 标记。如果由于某种原因原始页码未知或 SplitOnPages=false，则此属性始终包含“0”，表示转换器无法为提供的 HTML 标记文件提供准确的原始 PDF 页码。

**退货：**
int - 整数值
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


由转换器设置。从转换器到自定义方法代码的假定文件名 可以在自定义代码中使用，以决定如何处理或在何处保存内容

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


必要时应在自定义代码中设置。如果出于某些原因不应使用自定义代码处理提供的 html 标记，而是使用转换器代码本身以转换器方式的标准处理，则必须在自定义代码中将此标志设置为“true”。因此，如果在自定义代码中设置此标志意味着自定义代码未处理引用的文件并且转换器必须自行处理

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




### setContentStream(InputStream contentStream) {#setContentStream-java.io.InputStream-}
```
public void setContentStream(InputStream contentStream)
```


由转换器设置。表示保存为流的 HTML

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 输入流实例 |

### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


必要时应在自定义代码中设置。如果出于某些原因不应使用自定义代码处理提供的 html 标记，而是使用转换器代码本身以转换器方式的标准处理，则必须在自定义代码中将此标志设置为“true”。因此，如果在自定义代码中设置此标志意味着自定义代码未处理引用的文件并且转换器必须自行处理

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customProcessingCancelled | boolean | 布尔值 |

### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


由转换器设置。如果设置 SplitToPages 属性，则在创建转换期间创建多个 HTML 文件（每个转换页面一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可用于自定义代码的逻辑，以决定如何处理或在何处保存 HTML 页面，如果关闭页面拆分，则此值始终包含“1”，因为在这种情况下，整个源文档只会生成一个大的 HTML 页面.

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| htmlHostPageNumber | int | 整数值 |

### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


由转换器设置。如果设置了 SplitToPages 属性，则在创建转换期间会创建多个 HTML 文件（每个转换后的页面一个 HTML 文件）。此属性告诉自定义代码从原始 PDF 的哪一页创建保存的 HTML 标记。如果由于某种原因原始页码未知或 SplitOnPages=false，则此属性始终包含“0”，表示转换器无法为提供的 HTML 标记文件提供准确的原始 PDF 页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfHostPageNumber | int | 整数值 |

### setSupposedFileName(String supposedFileName) {#setSupposedFileName-java.lang.String-}
```
public void setSupposedFileName(String supposedFileName)
```


由转换器设置。从转换器到自定义方法代码的假定文件名 可以在自定义代码中使用，以决定如何处理或在何处保存内容

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| supposedFileName | java.lang.String | 字符串值 |

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
