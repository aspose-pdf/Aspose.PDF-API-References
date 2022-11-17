---
title: LoadOptions.ResourceLoadingResult
second_title: 用于 Java API 参考的 Aspose.PDF
description: 自定义加载资源的结果
type: docs
weight: 12
url: /zh/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**遗产：**
java.lang.Object
```
public static class LoadOptions.ResourceLoadingResult
```

自定义加载资源的结果
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceLoadingResult(byte[] data)](#ResourceLoadingResult-byte---) | 创建加载结果实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 使用自定义加载器加载的二进制数据 - 必须在加载后设置 |
| [getEncodingIfKnown()](#getEncodingIfKnown--) | 有时资源的编码在加载之后或期间是已知的。 |
| [getExceptionOfLoadingIfAny()](#getExceptionOfLoadingIfAny--) | 有时由于某种原因无法加载请求的资源。 |
| [getMIMETypeIfKnown()](#getMIMETypeIfKnown--) | 有时有关加载资源的 MIME 类型的知识对转换器很有用您可以在此参数中提供 MIME 类型（如果它在加载后已知）。 |
| [hashCode()](#hashCode--) |  |
| [isLoadingCancelled()](#isLoadingCancelled--) | 有时由于某些原因加载不应出现自定义代码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncodingIfKnown(Charset encodingIfKnown)](#setEncodingIfKnown-java.nio.charset.Charset-) | 有时资源的编码在加载之后或期间是已知的。 |
| [setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | 有时由于某种原因无法加载请求的资源。 |
| [setLoadingCancelled(boolean loadingCancelled)](#setLoadingCancelled-boolean-) | 有时由于某些原因加载不应出现自定义代码。 |
| [setMIMETypeIfKnown(String MIMETypeIfKnown)](#setMIMETypeIfKnown-java.lang.String-) | 有时有关加载资源的 MIME 类型的知识对转换器很有用您可以在此参数中提供 MIME 类型（如果它在加载后已知）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceLoadingResult(byte[] data) {#ResourceLoadingResult-byte---}
```
public ResourceLoadingResult(byte[] data)
```


创建加载结果实例

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 必须始终提供自定义加载的结果，如果无法获得任何结果，它可以是零长度数组 |

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
### getData() {#getData--}
```
public byte[] getData()
```


使用自定义加载器加载的二进制数据 - 必须在加载后设置

**退货：**
字节[- 字节值数组
### getEncodingIfKnown() {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```


有时资源的编码在加载之后或期间是已知的。在这种情况下，自定义代码可以通过此参数为转换器提供该知识。如果编码未知或无关紧要，您可以在此参数中保留 null。

**退货：**
java.nio.charset.Charset - 字符集实例
### getExceptionOfLoadingIfAny() {#getExceptionOfLoadingIfAny--}
```
public System.Exception getExceptionOfLoadingIfAny()
```


有时由于某种原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，并且无论如何都可以创建结果文档（但可能质量稍差，没有图像等）。如果在加载期间发生异常，只需捕获它并放入此参数 - 有时该信息对于转换器渲染结果很有用。

**退货：**
com.aspose.ms.System.Exception - 异常
### getMIMETypeIfKnown() {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```


有时有关加载资源的 MIME 类型的知识对转换器很有用您可以在此参数中提供 MIME 类型（如果它在加载后已知）。当 MIME 类型未知或不需要提供时，请将参数保留为 null。

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isLoadingCancelled() {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```


有时由于某些原因加载不应出现自定义代码。在这种情况下，请将此标志设置为 True。在这种情况下，转换器将尝试使用内部默认资源加载器来获得该结果（因为它在未提供自定义策略的情况下表现）。

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




### setEncodingIfKnown(Charset encodingIfKnown) {#setEncodingIfKnown-java.nio.charset.Charset-}
```
public void setEncodingIfKnown(Charset encodingIfKnown)
```


有时资源的编码在加载之后或期间是已知的。在这种情况下，自定义代码可以通过此参数为转换器提供该知识。如果编码未知或无关紧要，您可以在此参数中保留 null。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encodingIfKnown | java.nio.charset.Charset | 字符集实例 |

### setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny) {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
```
public void setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)
```


有时由于某种原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，并且无论如何都可以创建结果文档（但可能质量稍差，没有图像等）。如果在加载期间发生异常，只需捕获它并放入此参数 - 有时该信息对于转换器渲染结果很有用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| exceptionOfLoadingIfAny | com.aspose.ms.System.例外 | Exception |

### setLoadingCancelled(boolean loadingCancelled) {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```


有时由于某些原因加载不应出现自定义代码。在这种情况下，请将此标志设置为 True。在这种情况下，转换器将尝试使用内部默认资源加载器来获得该结果（因为它在未提供自定义策略的情况下表现）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| loadingCancelled | boolean | 布尔值 |

### setMIMETypeIfKnown(String MIMETypeIfKnown) {#setMIMETypeIfKnown-java.lang.String-}
```
public void setMIMETypeIfKnown(String MIMETypeIfKnown)
```


有时有关加载资源的 MIME 类型的知识对转换器很有用您可以在此参数中提供 MIME 类型（如果它在加载后已知）。当 MIME 类型未知或不需要提供时，请将参数保留为 null。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| MIMETypeIfKnown | java.lang.String | 字符串值 |

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
