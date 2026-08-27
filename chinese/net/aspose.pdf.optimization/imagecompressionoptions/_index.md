---
title: "类 ImageCompressionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions 类。该类包含用于图像压缩的一组选项。"
type: docs
weight: 8090
url: /zh/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

类包含用于图像压缩的一组选项。

```csharp
public class ImageCompressionOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | 获取或设置用于存储图像的编码。 |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | 在使用 CompressImages 标志时指定图像压缩级别。 |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | 指定图像的最大分辨率。如果图像分辨率更高，则会被缩放。 |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | 如果此标志设置为 true 且 CompressImages 为 true，则当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | 压缩算法的版本。可能的取值有：1. 标准压缩，2. fast（改进的压缩，比标准更快，但可能并不适用于所有图像），3. mixed（对无法使用更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 \"fast\" 算法更慢。版本 \"Fast\" 不适用于图像重新调整大小（将使用标准方法）。默认是 \"Standard\"）。 |

### 另请参见

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


