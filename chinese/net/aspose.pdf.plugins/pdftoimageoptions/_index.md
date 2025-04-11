---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToImageOptions class. 表示 PdfToImage 插件的选项
type: docs
weight: 9130
url: /zh/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

表示 [`PdfToImage`](../pdftoimage/) 插件的选项。

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件数据集合。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | 返回操作名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置处理的页面列表。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件数据集合添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是一个。如果要将图像保存到内存流中，请将 null 作为参数传递。 |

## Other Members

| Name | Description |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | 定义在将 PDF 文档转换为 Jpeg 图像时可以使用的不同模式。请参见 [`JpegOptions`](../jpegoptions/) 类。 |

## Remarks

PdfImageOptions 类包含添加表示输入 PDF 文档的数据（文件、流）的基本功能。

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)