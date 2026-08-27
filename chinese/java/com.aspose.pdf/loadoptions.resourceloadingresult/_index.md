---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF for Java API 参考"
description: "自定义加载资源的结果"
type: docs
weight: 2820
url: /zh/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

自定义加载资源的结果

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | 创建加载结果的实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getData](#getData--) | 使用自定义加载器加载的二进制数据——必须在加载后设置 |
| [getEncodingIfKnown](#getEncodingIfKnown--) | 有时资源的编码在加载后或加载期间才知道。在这种情况下，自定义代码可以通过此参数向转换器提供该编码信息。如果编码未知或不重要，可以将此参数设为 null。 |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | 有时由于某些原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，结果文档仍然可以创建（但可能质量稍差，缺少图像等）。如果在加载期间出现异常，只需捕获它并放入此参数——有时该信息对转换器渲染结果很有用。 |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | 有时已加载资源的 MIME 类型信息对转换器有用。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或无需提供时，请将参数设为 null。 |
| [isLoadingCancelled](#isLoadingCancelled--) | 有时由于某些原因不应执行自定义代码加载。在这种情况下请将此标志设为 True。此时转换器将尝试使用内部默认资源加载器获取结果（行为类似于未提供自定义策略的情况）。 |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | 有时资源的编码在加载后或加载期间才知道。在这种情况下，自定义代码可以通过此参数向转换器提供该编码信息。如果编码未知或不重要，可以将此参数设为 null。 |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | 有时由于某些原因无法加载请求的资源。 |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | 有时由于某些原因不应执行自定义代码加载。在这种情况下请将此标志设为 True。此时转换器将尝试使用内部默认资源加载器获取结果（行为类似于未提供自定义策略的情况）。 |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | 有时已加载资源的 MIME 类型信息对转换器有用。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或无需提供时，请将参数设为 null。 |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

创建加载结果的实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 |  | 必须始终提供自定义加载的结果；如果无法获得任何结果，可以是长度为零的数组。 |

### getData {#getData--}
```
public byte[] getData()
```

使用自定义加载器加载的二进制数据——必须在加载后设置

**Returns:**
字节值数组

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

有时资源的编码在加载后或加载期间才知道。在这种情况下，自定义代码可以通过此参数向转换器提供该编码信息。如果编码未知或不重要，可以将此参数设为 null。

**Returns:**
字符集实例

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

有时由于某些原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，结果文档仍然可以创建（但可能质量稍差，缺少图像等）。如果在加载期间出现异常，只需捕获它并放入此参数——有时该信息对转换器渲染结果很有用。

**Returns:**
异常

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

有时已加载资源的 MIME 类型信息对转换器有用。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或无需提供时，请将参数设为 null。

**Returns:**
字符串值

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

有时由于某些原因不应执行自定义代码加载。在这种情况下请将此标志设为 True。此时转换器将尝试使用内部默认资源加载器获取结果（行为类似于未提供自定义策略的情况）。

**Returns:**
布尔值

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
有时资源的编码在加载后或加载期间才知道。在这种情况下，自定义代码可以通过此参数向转换器提供该编码信息。如果编码未知或不重要，可以将此参数设为 null。

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
有时由于某些原因无法加载请求的资源。

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

有时由于某些原因不应执行自定义代码加载。在这种情况下请将此标志设为 True。此时转换器将尝试使用内部默认资源加载器获取结果（行为类似于未提供自定义策略的情况）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadingCancelled |  | 布尔值 |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
有时已加载资源的 MIME 类型信息对转换器有用。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或无需提供时，请将参数设为 null。
