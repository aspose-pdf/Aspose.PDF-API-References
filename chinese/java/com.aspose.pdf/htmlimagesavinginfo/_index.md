---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示与在 PDF 到 HTML 转换期间保存的外部资源图像文件相关的一组数据。
type: docs
weight: 17
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

此类表示在 PDF 到 HTML 转换期间与外部资源图像文件的保存相关的一组数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlImageSavingInfo()](#HtmlImageSavingInfo--) | 创建 HtmlImageSavingInfo 的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | 由转换器设置。 |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | 告诉自定义代码生成的 HTML 页面文件集的哪个页面属于保存的图像。 |
| [getImageType()](#getImageType--) | 表示在 HTML 中引用的已保存图像的类型。 |
| [getParentType()](#getParentType--) | 保存的图像可以属于 HTML 本身，也可以被提取。从 SVG 嵌入到 HTML。 |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | 告诉自定义代码原始 PDF 文档的哪一页属于保存的图像 因为可能不会保存原始文档的所有页面，这个值告诉我们原始 PDF 中的主机页码。 |
| [getResourceType()](#getResourceType--) | 由转换器设置。 |
| [getSupposedFileName()](#getSupposedFileName--) | 由转换器设置。 |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | 如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | 如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。 |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | 告诉自定义代码生成的 HTML 页面文件集的哪个页面属于保存的图像。 |
| [setImageType(int imageType)](#setImageType-int-) | 表示在 HTML 中引用的已保存图像的类型。 |
| [setParentType(int parentType)](#setParentType-int-) | 保存的图像可以属于 HTML 本身，也可以被提取。从 SVG 嵌入到 HTML。 |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | 告诉自定义代码原始 PDF 文档的哪一页属于保存的图像 因为可能不会保存原始文档的所有页面，这个值告诉我们原始 PDF 中的主机页码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlImageSavingInfo() {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```


创建 HtmlImageSavingInfo 的新实例

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
public byte[] getContentStream()
```


由转换器设置。表示已保存文件的二进制内容。

**退货：**
字节[] - 字节数组
### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


告诉自定义代码生成的 HTML 页面文件集的哪个页面属于保存的图像。如果关闭页面拆分，则此值始终包含“1”，因为在这种情况下只会生成一个 HTML 页面。

**退货：**
int - 整数值
### getImageType() {#getImageType--}
```
public int getImageType()
```


表示在 HTML 中引用的已保存图像的类型。由转换器设置，可以在自定义代码中使用来决定应该做什么

**退货：**
int - HtmlImageType 元素
### getParentType() {#getParentType--}
```
public int getParentType()
```


保存的图像可以属于 HTML 本身，也可以被提取。从 SVG 嵌入到 HTML。此属性可以告诉自定义代码处理图像的父级类型是什么。它由转换器设置，可以在自定义代码中使用来决定应该对该图像执行什么操作（fe 自定义代码可以决定将图像保存在何处或者必须如何在父内容中引用它）。

**退货：**
int - ImageParentTypes 元素
### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


告诉自定义代码原始 PDF 文档的哪一页属于保存的图像 因为可能不会保存原始文档的所有页面，这个值告诉我们原始 PDF 中的主机页码。如果由于某种原因原始页码未知，它总是返回 '1'

**退货：**
int - 整数值
### getResourceType() {#getResourceType--}
```
public int getResourceType()
```


由转换器设置。从转换器到自定义方法代码的假定文件名 可以在自定义代码中使用来决定如何处理或保存该文件

**退货：**
int - NodeLevelResourceType 元素
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


由转换器设置。从转换器到自定义方法代码的假定文件名 可以在自定义代码中使用来决定如何处理或保存该文件

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


如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。因此，它的设置设置为 true 意味着自定义代码不处理引用的文件并且转换器必须自己处理它（在这两种情况下 - 用于在某处保存和在引用文件中命名）。

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




### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。因此，它的设置设置为 true 意味着自定义代码不处理引用的文件并且转换器必须自己处理它（在两种意义上 - 用于保存某处和在引用文件中命名）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customProcessingCancelled | boolean | 布尔值 |

### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


告诉自定义代码生成的 HTML 页面文件集的哪个页面属于保存的图像。如果关闭页面拆分，则此值始终包含“1”，因为在这种情况下只会生成一个 HTML 页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| htmlHostPageNumber | int | 整数值 |

### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


表示在 HTML 中引用的已保存图像的类型。由转换器设置，可以在自定义代码中使用来决定应该做什么

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageType | int | HtmlImageType 元素 |

### setParentType(int parentType) {#setParentType-int-}
```
public void setParentType(int parentType)
```


保存的图像可以属于 HTML 本身，也可以被提取。从 SVG 嵌入到 HTML。此属性可以告诉自定义代码处理图像的父级类型是什么。它由转换器设置，可以在自定义代码中使用来决定应该对该图像执行什么操作（fe 自定义代码可以决定将图像保存在何处或者必须如何在父内容中引用它）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentType | int | ImageParentTypes 元素 |

### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


告诉自定义代码原始 PDF 文档的哪一页属于保存的图像 因为可能不会保存原始文档的所有页面，这个值告诉我们原始 PDF 中的主机页码。如果由于某种原因原始页码未知，它总是返回 '1'

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfHostPageNumber | int | 整数值 |

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
