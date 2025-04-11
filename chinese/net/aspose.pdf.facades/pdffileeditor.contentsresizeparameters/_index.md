---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters 类。用于指定页面调整大小参数的类。允许设置以下参数：结果页面的大小（宽度、高度），以默认空间单位或初始页面大小的百分比表示；左、上、下和右边距，以默认空间单位或初始页面大小的百分比表示；某些值可以留空以进行自动计算。这些值将在明确指定值后从页面大小的其余部分计算。例如，如果页面宽度为 100，指定的新页面宽度为 60 单位，则左边距和右边距将自动计算为 (100 - 60) / 2 = 15。此类用于 ResizeContents 方法。
type: docs
weight: 4480
url: /zh/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

用于指定页面调整大小参数的类。允许设置以下参数：结果页面的大小（宽度、高度），以默认空间单位或初始页面大小的百分比表示；左、上、下和右边距，以默认空间单位或初始页面大小的百分比表示；某些值可以留空以进行自动计算。这些值将在明确指定值后从页面大小的其余部分计算。例如：如果页面宽度 = 100，指定的新页面宽度为 60 单位，则左边距和右边距将自动计算为：(100 - 60) / 2 = 15。此类用于 ResizeContents 方法。

```csharp
public class ContentsResizeParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | 创建调整大小参数，其中所有值设置为“自动”。如果需要，可以稍后指定边距和内容大小。 |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 创建具有指定边距值和内容大小的调整大小参数。 |

## Properties

| Name | Description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 获取或设置结果页面的下边距。 |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 获取或设置结果页面上源页面内容的高度。 |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 获取或设置结果页面上源页面内容的宽度。 |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 获取或设置结果页面的左边距。 |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 获取或设置结果页面的右边距。 |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 获取或设置结果页面的上边距。 |

## Methods

| Name | Description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 创建具有指定内容大小的调整大小参数。 |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 创建具有指定内容大小的调整大小参数，以初始页面大小的百分比表示。边距自动计算。 |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 创建具有指定边距值的调整大小参数。内容大小自动计算。 |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | 创建调整大小参数。边距以初始页面大小的百分比表示。 |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | 创建用于页面调整大小的参数。 |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | 创建用于页面调整大小的参数。新大小以百分比表示。 |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)