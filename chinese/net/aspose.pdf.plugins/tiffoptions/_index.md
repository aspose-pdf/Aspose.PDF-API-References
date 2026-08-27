---
title: "类 TiffOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TiffOptions 类。表示 Pdf 到 Tiff 转换器的 Tiff 插件选项"
type: docs
weight: 9570
url: /zh/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

表示 Pdf 到 Tiff 转换器的 [`Tiff`](../tiff/) 插件选项。

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffOptions](tiffoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 获取或设置白色和黑色颜色转换的阈值。此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 获取或设置压缩类型。 |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | 获取或设置颜色深度。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件的数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 返回操作的名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置用于该过程的页面列表。 |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | 获取并设置允许将所有页面保存为单个多页 tiff 的标志。 |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | 获取或设置形状类型。 |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 获取或设置一个值，指示是否跳过空白页。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是 a 。如果想将图像保存到内存流中，请将参数设为 null。 |

### 另请参见

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


