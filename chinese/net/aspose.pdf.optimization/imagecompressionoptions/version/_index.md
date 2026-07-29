---
title: "ImageCompressionOptions.Version"
second_title: "Aspose.PDF for .NET API 参考"
description: "ImageCompressionOptions 属性。压缩算法的版本。可能的取值有：1. 标准压缩；2. 快速改进压缩，速度比标准快，但可能并非适用于所有图像；3. 混合压缩，对无法通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比快速算法更慢。快速版本不适用于图像缩放，将使用标准方法。默认是 Standard。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## ImageCompressionOptions.Version property

压缩算法的版本。可能的取值有：1. 标准压缩，2. fast（改进的压缩，比标准更快，但可能并不适用于所有图像），3. mixed（对无法使用更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比 \"fast\" 算法更慢。版本 \"Fast\" 不适用于图像重新调整大小（将使用标准方法）。默认是 \"Standard\"）。

```csharp
public ImageCompressionVersion Version { get; set; }
```

### 另请参见

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)


