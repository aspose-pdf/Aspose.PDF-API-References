---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions class. 类包含用于图像压缩的选项集
type: docs
weight: 7950
url: /zh/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

类包含用于图像压缩的选项集。

```csharp
public class ImageCompressionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | 获取或设置用于存储图像的编码。 |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | 指定使用 CompressIamges 标志时的图像压缩级别。 |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | 指定图像的最大分辨率。如果图像具有更高的分辨率，它将被缩放。 |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | 如果此标志设置为 true 且 CompressImages 为 true，当图像分辨率大于指定的 MaxResolution 参数时，图像将被调整大小。 |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | 压缩算法的版本。可能的值为：1. 标准压缩，2. 快速（改进的压缩，速度比标准快，但可能不适用于所有图像），3. 混合（标准压缩应用于无法通过更快算法压缩的图像，这可能提供最佳压缩，但比“快速”算法更慢。版本“快速”不适用于调整图像大小（将使用标准方法）。默认值为“标准”。 |

### See Also

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)