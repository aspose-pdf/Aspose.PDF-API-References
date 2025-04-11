---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions class. 表示 Pdf 到 Tiff 转换器选项，用于 Tiff 插件
type: docs
weight: 9420
url: /zh/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

表示 Pdf 到 Tiff 转换器选项，用于 [`Tiff`](../tiff/) 插件。

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 获取或设置白色和黑色转换的值边界。此参数可以与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 获取或设置压缩类型。 |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | 获取或设置颜色深度。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 返回操作名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置处理的页面列表。 |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | 获取和设置允许将所有页面保存为一个多页 tiff 的标志。 |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | 获取或设置形状的类型。 |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 获取或设置一个值，指示是否跳过空白页面。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是 . 如果要将图像保存到内存流中，请将 null 作为参数传递。 |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)