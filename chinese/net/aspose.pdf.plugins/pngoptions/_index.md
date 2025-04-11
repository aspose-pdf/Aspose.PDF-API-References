---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions 类。表示 Png 插件的 Pdf 到 Png 转换器选项
type: docs
weight: 9180
url: /zh/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions class

表示 Pdf 到 Png 转换器选项，用于 [`Png`](../png/) 插件。

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PngOptions](pngoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | 返回操作的名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置处理的页面列表。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是一个。如果要将图像保存到内存流中，请将 null 作为参数传递。 |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)