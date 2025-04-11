---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor class. 用于从 PDF 文档中提取图像和文本的类
type: docs
weight: 4450
url: /zh/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

用于从 PDF 文档中提取图像和文本的类。

```csharp
public sealed class PdfExtractor : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | 初始化新的 `PdfExtractor` 对象。 |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfExtractor` 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在处理的文档外观。 |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | 获取或设置提取操作将执行的页面范围的结束页。 |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | 设置提取图像过程的模式。 |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | 设置提取文本结果的模式。 |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | 当文本包含希伯来语或阿拉伯语符号时为真。此情况必须特别考虑，因为字符串函数会改变其行为，并开始从右到左处理文本（数字和其他非文本字符除外）。 |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | 获取或设置输入文件的密码。 |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | 设置或获取提取图像的分辨率。默认值为 150。分辨率值更大的图像更清晰。然而，增加分辨率值会导致提取图像所需的时间和内存增加。通常，为了获得清晰的图像，将分辨率设置为 150 或 300 就足够了。 |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | 获取或设置提取操作将执行的页面范围的起始页。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | 从流中绑定 PDF 文档。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | 绑定输入 PDF 文件。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | 从 PDF 文档中提取附件。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | 通过附件名称提取 PDF 文件的附件。 |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | 从 PDF 文件中提取图像。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | 使用 Unicode 编码从 PDF 文档中提取文本。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | 使用指定编码从 PDF 文档中提取文本。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | 将所有附件文件保存到流中。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | 将附件存储到文件中。 |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | 获取附件列表。 |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | 返回 PDF 文件中的附件列表。注意：必须在使用此方法之前调用 ExtractAttachments。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | 从 PDF 文件中检索下一个图像并将其存储到流中。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | 从 PDF 文档中检索下一个图像。注意：必须在使用此方法之前调用 ExtractImage。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | 从 PDF 文件中检索下一个图像并以给定图像格式将其存储到流中。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | 以给定图像格式从 PDF 文档中检索下一个图像。注意：必须在使用此方法之前调用 ExtractImage。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | 将一页的文本保存到流中。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | 将一页的文本保存到文件中。 |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | 将文本保存到流中。另见：[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | 将文本保存到文件中。另见：[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | 将文本保存到流中。另见：[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | 检查 PDF 文档中是否还有更多图像可用。注意：必须在使用此方法之前调用 ExtractImage。 |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | 指示是否可以获取更多文本。 |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)