---
title: "类 PdfFileMend"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileMend 类。表示用于在现有 PDF 文档的页面上添加文本和图像的类"
type: docs
weight: 4650
url: /zh/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

表示用于在现有 PDF 文档页面上添加文本和图像的类。

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | 构造函数。 |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | 在 *document* 的基础上初始化新的 `PdfFileMend` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | 设置一个 bool 值，以指示 AddText 方法中的自动换行。如果该值为 true，FormattedText 中的文本将自动换行。默认情况下，该值为 false。 |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | 设置或获取文本定位策略。[`PositioningMode`](../positioningmode/) 默认模式为 Legacy。 |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | 设置或获取换行算法。参见 WordWrapMode 和 IsWordWrap。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | 在指定坐标处向 PDF 文档的指定页面集合添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | 在指定坐标处向 PDF 文档的指定页面集合添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | 在指定坐标处向 PDF 文档的指定页面集合添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | 在指定坐标处向 PDF 文档的指定页面集合添加图像。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | 未实现。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | 未实现。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | 未实现。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | 关闭 PdfFileMend 对象。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | 将 PDF 文档保存到指定的流中。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | 将 PDF 文档保存到指定的文件中。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


