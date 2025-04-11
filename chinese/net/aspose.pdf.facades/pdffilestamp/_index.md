---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStamp 类。用于向 PDF 文件添加水印或背景的类
type: docs
weight: 4570
url: /zh/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp 类

用于向 PDF 文件添加水印（印章或背景）。

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | PdfFileStamp 的构造函数。可以通过相应的属性指定输入文件和输出文件。 |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfFileStamp` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存，而不进行转换。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | 如果为 true，则保持安全性。（此功能将在下一个版本中实现）。 |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | 获取或设置页码编号样式。可能的值：NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | 获取或设置优化标志。如果设置了此标志，则结果文件中的相等资源流将合并为一个 PDF 对象。这可以减少结果文件的大小，但可能导致执行速度变慢和更大的内存需求。默认值：false。 |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | 获取源文件中第一页的高度。 |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | 获取或设置页码的旋转。旋转以度为单位。默认值为 0。 |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | 获取输入文件中第一页的宽度。 |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | 下一个添加的印章的印章 ID（包括页面标题/页脚/页码）。 |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | 获取或设置输入文件中第一页的起始编号。后续页面将从此值开始编号。例如，如果 StartingNumber 设置为 100，则文档页面将编号为 100, 101, 102... |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | 向文档的页面添加页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | 将图像作为页面的页脚添加。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | 将图像作为文档页面的页脚添加。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | 向文档的页面添加页脚。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | 将图像作为页面的页脚添加。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | 将图像作为页面的页脚添加。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | 向页面添加页眉。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | 将图像作为页面的页眉添加。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | 将图像作为文件页面的页眉添加。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | 向文件的页面添加页眉。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | 在页面顶部添加图像。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | 将图像作为页面的页眉添加。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | 向页面添加页码。页码可以包含 # 符号，该符号将被页码替换。页码位于页面底部水平居中。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | 向文件添加页码。页码文本可以包含 # 符号，该符号将被页面编号替换。页码位于页面底部水平居中。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | 向页面添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | 向页面添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | 在页面的指定位置添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | 在页面的指定位置添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | 向文档的页面添加页码。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | 向文档的页面添加页码。 |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | 向文件添加印章。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | 关闭打开的文件并保存更改。警告。如果指定了输入或输出流，则它们不会被 Close() 方法关闭。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | 将文档保存到指定流中。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | 将结果保存到指定文件中。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | 左下位置。 |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | 中下位置。 |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | 右下位置。 |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | 左侧位置。 |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | 右侧位置。 |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | 左上位置。 |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | 中上位置。 |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | 右上位置。 |

### 另请参见

* 类 [SaveableFacade](../saveablefacade/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)