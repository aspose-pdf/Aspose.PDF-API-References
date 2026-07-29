---
title: "类 PdfExtractor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfExtractor 类。用于从 PDF Document 中提取图像和文本的类"
type: docs
weight: 4570
url: /zh/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

用于从 PDF 文档中提取图像和文本的类。

```csharp
public sealed class PdfExtractor : Facade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | 初始化新的 `PdfExtractor` 对象。 |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | 在 *document* 的基础上初始化新的 `PdfExtractor` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | 获取或设置将在其执行提取操作的页面范围的结束页。 |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | 设置图像提取过程的模式。 |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | 设置文本提取结果的模式。 |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | 当文本包含希伯来或阿拉伯符号时为 true。必须特别考虑这种情况，因为字符串函数会改变其行为，并从右向左处理文本（数字和其他非文本字符除外）。 |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | 获取或设置输入文件的密码。 |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | 设置或获取提取图像的分辨率。默认值为 150。分辨率更高的图像会更清晰。然而，提高分辨率会导致提取图像所需的时间和内存增加。通常，要获得清晰的图像，只需将分辨率设置为 150 或 300。 |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | 获取或设置将在其范围内执行提取操作的起始页。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | 从流绑定 PDF 文档。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | 绑定输入 PDF 文件。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | 从 PDF 文档中提取附件。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | 按附件名称将附件提取到 PDF 文件。 |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | 从 PDF 文件中提取图像。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | 使用 Unicode 编码从 PDF 文档中提取文本。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | 使用指定编码从 PDF 文档中提取文本。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | 将所有附件文件保存到流中。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | 将附件存储到文件中。 |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | 获取附件列表。 |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | 返回 PDF 文件中的附件列表。注意：在使用此方法之前必须先调用 ExtractAttachments。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | 检索 PDF 文件中的下一张图像并将其存入流中。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | 检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须先调用 ExtractImage。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | 检索 PDF 文件中的下一张图像并使用给定的图像格式将其存入流中。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | 检索 PDF 文档中的下一张图像并使用给定的图像格式。注意：在使用此方法之前必须先调用 ExtractImage。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | 将单页文本保存到流中。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | 将单页文本保存到文件中。 |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | 将文本保存到流中。另请参阅：[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | 将文本保存到文件中。另请参阅：[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | 将文本保存到流中。另请参阅：[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | 检查 PDF 文档中是否还有可访问的图像。注意：在使用此方法之前必须先调用 ExtractImage。 |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | 指示是否可以获取更多文本。 |

### 另请参见

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


