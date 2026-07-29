---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "描述文档优化算法的类。该类的实例可用作 OptimizeResources() 方法的参数。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

描述文档优化算法的类。该类的实例可用作 OptimizeResources() 方法的参数。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [all](#all--) | 创建一个所有选项均已激活的优化策略。请注意，仅激活不会改变文档任何功能的选项。例如，图像压缩和字体未嵌入将不会启用（可以手动嵌入）。 |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | 如果设置为 {@link}，所有未压缩的页面内容流将在 {@code Document#OptimizeResources()} 期间使用 FlateDecode 过滤器进行压缩。默认是 {@link}，以保持向后兼容性。 |
| [getImageCompressionOptions](#getImageCompressionOptions--) | 描述文档中图像是否压缩以及压缩参数的一组选项。 |
| [getImageEncoding](#getImageEncoding--) | 将使用的图像编码。 |
| [getImageQuality](#getImageQuality--) | 在使用 CompressIamges 标志时指定图像压缩级别。 |
| [getMaxResoultion](#getMaxResoultion--) | 指定图像的最大分辨率。如果图像分辨率更高，则会进行缩放。 |
| [isAllowReusePageContent](#isAllowReusePageContent--) | 如果为 true，则在文档针对相同页面进行优化时会复用页面内容。 |
| [isCompressImages](#isCompressImages--) | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| [isCompressObjects](#isCompressObjects--) | 如果此标志设置为 {@code }，PDF 对象将被打包到对象流中并压缩，以减小 PDF 文件大小。 |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | 如果此标志设置为 true，资源流将被分析。如果发现重复的流（即流内容相同），这些流将合并为一个对象。这可以在某些情况下减小文档大小（例如，当同一文档被多次拼接时）。 |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | 移除私有信息（页面片段信息）。 |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | 如果此标志设置为 true，将检查所有文档对象，并删除未使用的对象（即没有任何引用的对象）。 |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | 如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。这可能会在例如从文档中提取页面时减小文档大小。 |
| [isResizeImages](#isResizeImages--) | 如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率高于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| [isSubsetFonts](#isSubsetFonts--) | 如果设置为 true，字体将被转换为子集。 |
| [isUnembedFonts](#isUnembedFonts--) | 如果设置为 true，使字体不嵌入。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | 如果为 true，则在文档针对相同页面进行优化时会复用页面内容。 |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | 如果设置为 {@link}，所有未压缩的页面内容流将在 {@code Document#OptimizeResources()} 期间使用 FlateDecode 过滤器进行压缩。默认是 {@link}，以保持向后兼容性。 |
| [setCompressImages](#setCompressImages-boolean-) | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| [setCompressObjects](#setCompressObjects-boolean-) | 如果此标志设置为 {@code }，PDF 对象将被打包到对象流中并压缩，以减小 PDF 文件大小。 |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | 描述文档中图像是否压缩以及压缩参数的一组选项。 |
| [setImageEncoding](#setImageEncoding-int-) | 将使用的图像编码。 |
| [setImageQuality](#setImageQuality-int-) | 在使用 CompressIamges 标志时指定图像压缩级别。 |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | 如果此标志设置为 true，资源流将被分析。如果发现重复的流（即流内容相同），这些流将合并为一个对象。这可以在某些情况下减小文档大小（例如，当同一文档被多次拼接时）。 |
| [setMaxResoultion](#setMaxResoultion-int-) | 指定图像的最大分辨率。如果图像分辨率更高，则会进行缩放。 |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | 移除私有信息（页面片段信息）。 |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | 如果此标志设置为 true，将检查所有文档对象，并删除未使用的对象（即没有任何引用的对象）。 |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | 如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。这可能会在例如从文档中提取页面时减小文档大小。 |
| [setResizeImages](#setResizeImages-boolean-) | 如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率高于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| [setSubsetFonts](#setSubsetFonts-boolean-) | 如果设置为 true，字体将被转换为子集。 |
| [setUnembedFonts](#setUnembedFonts-boolean-) | 如果设置为 true，使字体不嵌入。 |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

创建一个所有选项均已激活的优化策略。请注意，仅激活不会改变文档任何功能的选项。例如，图像压缩和字体未嵌入将不会启用（可以手动嵌入）。

**Returns:**
OptimizationOptions 对象。

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

如果设置为 {@link}，所有未压缩的页面内容流将在 {@code Document#OptimizeResources()} 期间使用 FlateDecode 过滤器进行压缩。默认是 {@link}，以保持向后兼容性。

**Returns:**
布尔值

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

描述文档中图像是否压缩以及压缩参数的一组选项。

**Returns:**
ImageCompressionOptions 实例

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

将使用的图像编码。

**Returns:**
ImageEncoding 元素

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

在使用 CompressIamges 标志时指定图像压缩级别。

**Returns:**
int 值 @deprecated 请使用 ImageCompressionOptions.ImageQuality 代替。

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

指定图像的最大分辨率。如果图像分辨率更高，则会进行缩放。

**Returns:**
int 值

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

如果为 true，则在文档针对相同页面进行优化时会复用页面内容。

**Returns:**
布尔值

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。

**Returns:**
boolean 值 @deprecated 请使用 ImageCompressionOptions.CompressImages 代替。

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

如果此标志设置为 {@code }，PDF 对象将被打包到对象流中并压缩，以减小 PDF 文件大小。

**Returns:**
布尔值

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

如果此标志设置为 true，资源流将被分析。如果发现重复的流（即流内容相同），这些流将合并为一个对象。这可以在某些情况下减小文档大小（例如，当同一文档被多次拼接时）。

**Returns:**
布尔值

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

移除私有信息（页面片段信息）。

**Returns:**
布尔值

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

如果此标志设置为 true，将检查所有文档对象，并删除未使用的对象（即没有任何引用的对象）。

**Returns:**
布尔值

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。这可能会在例如从文档中提取页面时减小文档大小。

**Returns:**
布尔值

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率高于指定的 MaxResolution 参数时，图像将被重新调整大小。

**Returns:**
boolean 值 @deprecated 请使用 ImageCompressionOptions.ResizeImages 代替。

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

如果设置为 true，字体将被转换为子集。

**Returns:**
布尔值

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

如果设置为 true，使字体不嵌入。

**Returns:**
布尔值

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

如果为 true，则在文档针对相同页面进行优化时会复用页面内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

如果设置为 {@link}，所有未压缩的页面内容流将在 {@code Document#OptimizeResources()} 期间使用 FlateDecode 过滤器进行压缩。默认是 {@link}，以保持向后兼容性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | boolean 值 @deprecated 请使用 ImageCompressionOptions.CompressImages 代替。 |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

如果此标志设置为 {@code }，PDF 对象将被打包到对象流中并压缩，以减小 PDF 文件大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
描述文档中图像是否压缩以及压缩参数的一组选项。

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

将使用的图像编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ImageEncoding 元素 |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

在使用 CompressIamges 标志时指定图像压缩级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @deprecated 请使用 ImageCompressionOptions.ImageQuality 代替。 |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

如果此标志设置为 true，资源流将被分析。如果发现重复的流（即流内容相同），这些流将合并为一个对象。这可以在某些情况下减小文档大小（例如，当同一文档被多次拼接时）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

指定图像的最大分辨率。如果图像分辨率更高，则会进行缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

移除私有信息（页面片段信息）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

如果此标志设置为 true，将检查所有文档对象，并删除未使用的对象（即没有任何引用的对象）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。这可能会在例如从文档中提取页面时减小文档大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率高于指定的 MaxResolution 参数时，图像将被重新调整大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | boolean 值 @deprecated 请使用 ImageCompressionOptions.ResizeImages 代替。 |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

如果设置为 true，字体将被转换为子集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

如果设置为 true，使字体不嵌入。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
