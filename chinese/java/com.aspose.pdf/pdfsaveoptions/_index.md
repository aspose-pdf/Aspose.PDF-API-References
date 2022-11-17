---
title: PdfSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 Pdf 格式的保存选项
type: docs
weight: 280
url: /zh/java/com.aspose.pdf/pdfsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

导出为 Pdf 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | 计算机上没有的字体默认使用的字体名称。 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getTempPath()](#getTempPath--) | 临时文件的路径。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | 计算机上没有的字体默认使用的字体名称。 |
| [setTempPath(String value)](#setTempPath-java.lang.String-) | 临时文件的路径。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


构造函数

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
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


计算机上没有的字体默认使用的字体名称。当保存为 PDF 的 PDF 文档包含文档本身和设备上不可用的字体时，API 会用默认字体替换此字体（如果在设备上找到具有 DefaultFontName 的字体）

**退货：**
java.lang.String - 字符串值
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


数据保存格式。

**退货：**
[SaveFormat](../../com.aspose.pdf/saveformat) 保存格式值
### getTempPath() {#getTempPath--}
```
public final String getTempPath()
```


临时文件的路径。

**退货：**
java.lang.String - 字符串值
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


获取布尔值，该值指示在文档保存到响应后将关闭响应对象。

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




### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


设置布尔值，指示在文档保存到响应后将关闭响应对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


计算机上没有的字体默认使用的字体名称。当保存为 PDF 的 PDF 文档包含文档本身和设备上不可用的字体时，API 会用默认字体替换此字体（如果在设备上找到具有 DefaultFontName 的字体）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTempPath(String value) {#setTempPath-java.lang.String-}
```
public final void setTempPath(String value)
```


临时文件的路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback 值 |

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
