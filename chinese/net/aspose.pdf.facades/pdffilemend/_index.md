---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend class. 表示一个用于在现有 PDF 文档的页面上添加文本和图像的类
type: docs
weight: 4530
url: /zh/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

表示一个用于在现有 PDF 文档的页面上添加文本和图像的类。

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | 构造函数。 |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfFileMend` 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | 设置一个布尔值，指示 AddText 方法中的换行。如果值为 true，FormattedText 中的文本将换行。默认值为 false。 |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | 设置或获取文本定位策略。 [`PositioningMode`](../positioningmode/) 默认模式为 Legacy。 |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | 设置或获取换行算法。请参见 WordWrapMode 和 IsWordWrap。 |

## Methods

| Name | Description |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | 在指定坐标的 PDF 文档指定页面上添加图像。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | 未实现。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | 未实现。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | 未实现。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | 关闭 PdfFileMend 对象。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | 将 PDF 文档保存到指定流。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | 将 PDF 文档保存到指定文件。 |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)