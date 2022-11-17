---
title: SvgSaveOptions.SvgImageSavingInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示与在 PDF 到 HTML 转换期间保存的外部资源图像文件相关的一组数据。
type: docs
weight: 11
url: /zh/java/com.aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class SvgSaveOptions.SvgImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

此类表示在 PDF 到 HTML 转换期间与外部资源图像文件的保存相关的一组数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgImageSavingInfo()](#SvgImageSavingInfo--) | 创建 HtmlImageSavingInfo 的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | 由转换器设置。 |
| [getImageType()](#getImageType--) | 表示在 HTML 中引用的类型 os 保存的图像。 |
| [getResourceType()](#getResourceType--) | 由转换器设置。 |
| [getSupposedFileName()](#getSupposedFileName--) | 由转换器设置。 |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | 如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | 如果由于某些原因建议的文件不使用自定义代码而是使用转换器代码本身以转换器方式的标准进行处理，则此标志必须在自定义代码中设置为“true”。 |
| [setImageType(int imageType)](#setImageType-int-) | 表示在 HTML 中引用的类型 os 保存的图像。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgImageSavingInfo() {#SvgImageSavingInfo--}
```
public SvgImageSavingInfo()
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
### getImageType() {#getImageType--}
```
public int getImageType()
```


表示在 HTML 中引用的类型 os 保存的图像。由转换器设置，可以在自定义代码中使用来决定应该做什么

**退货：**
int - SvgExternalImageType 元素
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

### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


表示在 HTML 中引用的类型 os 保存的图像。由转换器设置，可以在自定义代码中使用来决定应该做什么

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageType | int | SvgExternalImageType 元素 |

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
