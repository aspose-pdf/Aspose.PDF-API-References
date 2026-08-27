---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "描述文档优化算法的类。此类的实例可用作 OptimizeResources() 方法的参数。@deprecated 此类已过时。请。"
type: docs
weight: 1110
url: /zh/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

描述文档优化算法的类。此类的实例可用作 OptimizeResources() 方法的参数。@deprecated 此类已过时。请改用 com.aspose.pdf.optimization.OptimizationOptions。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | 已弃用。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [all](#all--) | 创建已激活所有选项的优化策略。 |
| [getMaximumImageDimension](#getMaximumImageDimension--) | 指定最大图像尺寸。如果现有图像的宽度或高度大于此值，图像尺寸将按比例缩小。 |
| [getResolution](#getResolution--) | 在使用 CompressIamges 标志时指定新的图像 DPI。 |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | 指定最大图像尺寸。如果现有图像的宽度或高度大于此值，图像尺寸将按比例缩小。 |
| [setResolution](#setResolution-int-) | 在使用 CompressIamges 标志时指定新的图像 DPI。 |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

已弃用。

### all {#all--}
```
public static Document.OptimizationOptions all()
```

创建已激活所有选项的优化策略。

**Returns:**
OptimizationOptions 对象。

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

指定最大图像尺寸。如果现有图像的宽度或高度大于此值，图像尺寸将按比例缩小。

**Returns:**
图像最大尺寸

### getResolution {#getResolution--}
```
public int getResolution()
```

在使用 CompressIamges 标志时指定新的图像 DPI。

**Returns:**
图像分辨率

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

指定最大图像尺寸。如果现有图像的宽度或高度大于此值，图像尺寸将按比例缩小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 尺寸 |  | 图像最大尺寸 |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

在使用 CompressIamges 标志时指定新的图像 DPI。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| DPI |  | 图像分辨率 |
