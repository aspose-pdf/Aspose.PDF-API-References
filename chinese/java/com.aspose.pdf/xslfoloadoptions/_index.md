---
title: XslFoLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 XSL-FO 文件加载/导入 pdf 文档的选项。
type: docs
weight: 429
url: /zh/java/com.aspose.pdf/xslfoloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions), [com.aspose.pdf.XmlLoadOptions](../../com.aspose.pdf/xmlloadoptions)
```
public final class XslFoLoadOptions extends XmlLoadOptions
```

表示将 XSL-FO 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XslFoLoadOptions()](#XslFoLoadOptions--) | 创建没有 xsl 数据的 XslFoLoadOptions 对象。 |
| [XslFoLoadOptions(String xslFile)](#XslFoLoadOptions-java.lang.String-) | 使用 xsl 数据创建 XslFoLoadOptions 对象。 |
| [XslFoLoadOptions(InputStream xslStream)](#XslFoLoadOptions-java.io.InputStream-) | 使用 xsl 数据创建 XslFoLoadOptions 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 关闭实例 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | 基本路径/url，从中搜索加载的 SVG 文件中引用的外部资源（如果有）的相对路径。 |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getParsingErrorsHandlingType()](#getParsingErrorsHandlingType--) | 源 XSLFO 文档可能包含格式错误。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [getXslStream()](#getXslStream--) | 获取用于将 xml 转换为 pdf 文档的 xsl 数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(String value)](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType(int parsingErrorsHandlingType)](#setParsingErrorsHandlingType-int-) | 源 XSLFO 文档可能包含格式错误。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XslFoLoadOptions() {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```


创建没有 xsl 数据的 XslFoLoadOptions 对象。

### XslFoLoadOptions(String xslFile) {#XslFoLoadOptions-java.lang.String-}
```
public XslFoLoadOptions(String xslFile)
```


使用 xsl 数据创建 XslFoLoadOptions 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xslFile | java.lang.String | Xsl 文件将 XSL-FO 文档转换为 pdf 文档。 |

### XslFoLoadOptions(InputStream xslStream) {#XslFoLoadOptions-java.io.InputStream-}
```
public XslFoLoadOptions(InputStream xslStream)
```


使用 xsl 数据创建 XslFoLoadOptions 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xslStream | java.io.InputStream | Xsl 流将 XSL-FO 文档转换为 pdf 文档。 |

### close() {#close--}
```
public void close()
```


关闭实例

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
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


基本路径/url，从中搜索加载的 SVG 文件中引用的外部资源（如果有）的相对路径。

**退货：**
java.lang.String - 字符串
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
### getParsingErrorsHandlingType() {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```


源 XSLFO 文档可能包含格式错误。此枚举列举了处理该错误的可能策略

**退货：**
int - ParsingErrorsHandlingTypes 元素
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### getXslStream() {#getXslStream--}
```
public InputStream getXslStream()
```


获取用于将 xml 转换为 pdf 文档的 xsl 数据。

**退货：**
java.io.InputStream - 输入流
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




### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public void setBasePath(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setParsingErrorsHandlingType(int parsingErrorsHandlingType) {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```


源 XSLFO 文档可能包含格式错误。此枚举列举了处理该错误的可能策略

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parsingErrorsHandlingType | int | ParsingErrorsHandlingTypes 元素 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

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
