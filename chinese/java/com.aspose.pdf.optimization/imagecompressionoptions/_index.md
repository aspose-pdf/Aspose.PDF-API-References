---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "类包含图像压缩的设置选项。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

类包含图像压缩的设置选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncoding](#getEncoding--) | 获取或设置用于存储图像的编码。 |
| [getImageQuality](#getImageQuality--) | 指定在使用 CompressImages 标志时的图像压缩级别。 |
| [getMaxResolution](#getMaxResolution--) | 指定图像的最大分辨率。如果图像的分辨率更高，则会被缩放。 |
| [getResizeImages](#getResizeImages--) | 如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| [getVersion](#getVersion--) | 压缩算法的版本。可能的取值有：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能并非适用于所有图像），3. 混合（对不能通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 "fast" 算法更慢。版本 "Fast" 不适用于调整图像大小（将使用标准方法）。默认是 "Standard"。） |
| [isCompressImages](#isCompressImages--) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [setCompressImages](#setCompressImages-boolean-) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [setEncoding](#setEncoding-int-) | 获取或设置用于存储图像的编码。 |
| [setImageQuality](#setImageQuality-int-) | 指定在使用 CompressImages 标志时的图像压缩级别。 |
| [setMaxResolution](#setMaxResolution-int-) | 指定图像的最大分辨率。如果图像的分辨率更高，则会被缩放。 |
| [setResizeImages](#setResizeImages-boolean-) | 如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| [setVersion](#setVersion-int-) | 压缩算法的版本。可能的取值有：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能并非适用于所有图像），3. 混合（对不能通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 "fast" 算法更慢。版本 "Fast" 不适用于调整图像大小（将使用标准方法）。默认是 "Standard"。） |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

获取或设置用于存储图像的编码。

**Returns:**
ImageEncoding 元素

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

指定在使用 CompressImages 标志时的图像压缩级别。

**Returns:**
int 值

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

指定图像的最大分辨率。如果图像的分辨率更高，则会被缩放。

**Returns:**
int 值

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。

**Returns:**
布尔值

### getVersion {#getVersion--}
```
public final int getVersion()
```

压缩算法的版本。可能的取值有：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能并非适用于所有图像），3. 混合（对不能通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 "fast" 算法更慢。版本 "Fast" 不适用于调整图像大小（将使用标准方法）。默认是 "Standard"。）

**Returns:**
int 值

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

**Returns:**
布尔值

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

获取或设置用于存储图像的编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ImageEncoding 元素 |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

指定在使用 CompressImages 标志时的图像压缩级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

指定图像的最大分辨率。如果图像的分辨率更高，则会被缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

压缩算法的版本。可能的取值有：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能并非适用于所有图像），3. 混合（对不能通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 "fast" 算法更慢。版本 "Fast" 不适用于调整图像大小（将使用标准方法）。默认是 "Standard"。）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
