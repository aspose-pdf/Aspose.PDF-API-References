---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions class. 表示 Pdf 到 Jpeg 转换器选项，用于 Jpeg 插件
type: docs
weight: 8920
url: /zh/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions class

表示 Pdf 到 Jpeg 转换器选项，用于 [`Jpeg`](../jpeg/) 插件。

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegOptions](jpegoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | 返回操作的名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置处理的页面列表。 |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | 获取和设置 Jpeg 质量 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是一个。如果您想将图像保存到内存流中，请将 null 作为参数传递。 |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)