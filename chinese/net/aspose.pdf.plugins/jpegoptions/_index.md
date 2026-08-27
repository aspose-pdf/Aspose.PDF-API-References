---
title: "类 JpegOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.JpegOptions 类。表示用于 Jpeg 插件的 Pdf 到 Jpeg 转换器选项。"
type: docs
weight: 9050
url: /zh/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions class

表示用于 [`Jpeg`](../jpeg/) 插件的 Pdf 到 Jpeg 转换器选项。

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JpegOptions](jpegoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 获取图像转换模式。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | 返回 [`PdfToImage`](../pdftoimage/) 插件的数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | 返回操作的名称。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 获取或设置生成图像的分辨率值。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 获取或设置用于该过程的页面列表。 |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | 获取和设置 Jpeg 质量 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | 向 [`PdfToImage`](../pdftoimage/) 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 设置新的保存数据源。只能是 a 。如果想将图像保存到内存流中，请将参数设为 null。 |

### 另请参见

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


