---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: ImageCompressionOptions 属性。压缩算法的版本。可能的值为 1. 标准压缩 2. 快速改进压缩，比标准更快，但可能不适用于所有图像 3. 混合标准压缩，应用于无法通过更快算法压缩的图像，这可能提供最佳压缩，但比快速算法更慢。版本快速不适用于调整图像大小，将使用标准方法。默认值为标准。
type: docs
weight: 70
url: /zh/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## ImageCompressionOptions.Version 属性

压缩算法的版本。可能的值为：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能不适用于所有图像），3. 混合（标准压缩应用于无法通过更快算法压缩的图像，这可能提供最佳压缩，但比“快速”算法更慢。版本“快速”不适用于调整图像大小（将使用标准方法）。默认值为“标准”。

```csharp
public ImageCompressionVersion Version { get; set; }
```

### 另请参阅

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)