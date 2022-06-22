---
title: PdfFileStamp
second_title: Aspose.PDF for .NET API 参考
description: 用于向 PDF 文件添加图章水印或背景的类
type: docs
weight: 2580
url: /zh/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

用于向 PDF 文件添加图章（水印或背景）的类。

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | PdfFileStamp 的构造函数。 输入文件和输出文件可以通过相应的属性来指定。  &lt;code&gt; PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.InputFile = "input.pdf"; fileStamp.OutputFile = "output.pdf"; &lt;/code&gt; |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | 在*document*的基础上初始化新的[`PdfFileStamp`](../pdffilestamp)对象。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | 当操作结果作为附件存储到 HttpResponse 对象中时，获取或设置附件的名称。 |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | 获取或设置将操作结果存储到 HttpResponse 对象中时内容的存储方式。可能的值:内联/附件。 默认值:内联。 |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。 如果未指定此属性，则文件将保存为默认 PDF 格式而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | 获取正在处理的文档外观。 |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | 如果为真，则保持安全性。 （此功能将在下一个版本中实现）。 |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | 获取或设置页面编号样式。可能的值:NumeralsArabic、NumeralsRomanUppercase、NumeralsRomanLowercase、LettersAppercase、LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | 获取或设置优化标志。如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。 这可以减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。 默认值:假。 |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | 获取源文件首页的高度。 |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | 获取或设置页码旋转。旋转以度为单位。默认值为 0。 |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | 获取输入文件第一页的宽度。 |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | 获取或设置将存储操作结果的响应对象。 |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | 当结果存储为 HttpResponse 时获取或设置保存选项。 默认值:PdfSaveOptions。 |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | 下一个添加戳记的戳记 ID（包括页眉/猫头鹰/页码）。 |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | 获取或设置输入文件第一页的起始编号。下一页将从该值开始编号。 例如，如果 StartingNumber 设置为 100，则文档页面将具有编号 100、101、102... |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | 为文档页面添加页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | 添加图像作为页面的页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | 将图像作为页脚添加到文档页面。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | 为文档页面添加页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | 添加图像作为页面的页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | 添加图像作为页面的页脚。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | 将页眉添加到页面。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | 在页面上添加图像作为标题。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | 将图像作为标题添加到文件的页面。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | 将页眉添加到文件页面。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | 在页面顶部添加图像。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | 在页面上添加图像作为标题。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | 将页码添加到页面。页码可能包含 # 符号，该符号将替换为页码。 页码放置在页面底部水平居中。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | 将页码添加到文件中。页码文本可能包含 # 符号，该符号将替换为页码。 页码放置在页面底部水平居中。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | 将页码添加到页面。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | 将页码添加到页面。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | 在页面的指定位置添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | 在页面的指定位置添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | 将页码添加到文档页面。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | 将页码添加到文档页面。 |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | 将戳记添加到文件中。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | 关闭打开的文件并保存更改。 警告。如果指定了输入或输出流，它们不会被 Close() 方法关闭。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | 配置外观。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | 将文档保存到指定的流中。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | 将结果保存到指定文件中。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | 左下位置。 |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | 底部中间位置。 |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | 右下位置。 |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | 左侧位置。 |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | 正确位置。 |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | 上让位置。 |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | 中上位置。 |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | 右上位置。 |

### 也可以看看

* class [SaveableFacade](../saveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
