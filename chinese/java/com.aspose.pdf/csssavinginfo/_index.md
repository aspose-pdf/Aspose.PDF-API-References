---
title: HtmlSaveOptions.CssSavingInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示与 PDF 转换为 HTML 格式期间自定义保存 CSS 相关的一组数据
type: docs
weight: 11
url: /zh/java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**遗产：**
java.lang.Object
```
public static class HtmlSaveOptions.CssSavingInfo
```

此类表示与 PDF 转换为 HTML 格式期间自定义保存 CSS 相关的一组数据
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | 由转换器设置。 |
| [getCssNumber()](#getCssNumber--) | 由转换器设置。 |
| [getSupposedURL()](#getSupposedURL--) | 由转换器设置。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContentStream(InputStream contentStream)](#setContentStream-java.io.InputStream-) | 由转换器设置。 |
| [setCssNumber(int cssNumber)](#setCssNumber-int-) | 由转换器设置。 |
| [setSupposedURL(String supposedURL)](#setSupposedURL-java.lang.String-) | 由转换器设置。 |
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


由转换器设置。表示保存的 CSS 的二进制内容

**退货：**
java.io.InputStream - InputStream 实例
### getCssNumber() {#getCssNumber--}
```
public int getCssNumber()
```


由转换器设置。在转换过程中会创建几个 CSS 文件。此属性显示转换期间保存的 CSS 文件的序号。可用于自定义代码的逻辑，决定如何处理或保存CSS内容

**退货：**
int - 整数值
### getSupposedURL() {#getSupposedURL--}
```
public String getSupposedURL()
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


由转换器设置。表示保存的 CSS 的二进制内容

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 输入流实例 |

### setCssNumber(int cssNumber) {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```


由转换器设置。在转换过程中会创建几个 CSS 文件。此属性显示转换期间保存的 CSS 文件的序号。可用于自定义代码的逻辑，决定如何处理或保存CSS内容

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cssNumber | int | 整数值 |

### setSupposedURL(String supposedURL) {#setSupposedURL-java.lang.String-}
```
public void setSupposedURL(String supposedURL)
```


由转换器设置。从转换器到自定义方法代码的假定文件名 可以在自定义代码中使用，以决定如何处理或在何处保存内容

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| supposedURL | java.lang.String | 字符串值 |

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
