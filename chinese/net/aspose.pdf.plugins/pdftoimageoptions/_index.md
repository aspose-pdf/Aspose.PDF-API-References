---
title: "类 PdfToImageOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfToImageOptions 类。表示 PdfToImage 插件的选项"
type: docs
weight: 9280
url: /zh/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

表示 [`PdfToImage`](../pdftoimage/) 插件的选项。

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件的数据集合。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | 返回操作名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置用于该过程的页面列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是 a 。如果想将图像保存到内存流中，请将参数设为 null。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | 定义在将 PDF 文档转换为 Jpeg 图像时可使用的不同模式。参见 [`JpegOptions`](../jpegoptions/) 类。 |

## 备注

PdfImageOptions 类包含用于添加表示输入 PDF 文档的数据（文件、流）的基础功能。

### 另请参见

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


