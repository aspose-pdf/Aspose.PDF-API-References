---
title: "类 PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters 类。用于指定 Page 调整大小参数的类。允许设置以下参数：结果 Page 的宽度和高度（以默认空间单位或初始 Pages 尺寸的百分比表示），左、上、下、右边距（以默认空间单位或初始 Page 尺寸的百分比表示）。某些值可以为 null，以便自动计算。这些值将在显式指定的值计算后，从剩余 Page 尺寸中计算。例如，如果 Page 宽度为 100，且新 Page 宽度指定为 60 单位，则左、右边距会自动计算为 (100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。"
type: docs
weight: 4600
url: /zh/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

用于指定 Page 调整大小参数的类。允许设置以下参数：结果 Page 的尺寸（宽度、高度），以默认空间单位或初始 Pages 尺寸的百分比表示；左、上、下、右边距，以默认空间单位或初始 Page 尺寸的百分比表示；某些值可以为 null，以便自动计算。这些值将在显式指定的值计算后，从剩余 Page 尺寸中计算。例如：如果 Page 宽度 = 100，且新 Page 宽度指定为 60 单位，则左、右边距会自动计算为 (100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。

```csharp
public class ContentsResizeParameters
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | 创建所有值设置为 “auto” 的调整大小参数。以后可以根据需要指定边距和内容尺寸。 |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 创建具有指定边距值和内容尺寸的调整大小参数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 获取或设置结果 Page 的底部边距。 |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 获取或设置结果 Page 上源 Page 内容的高度。 |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 获取或设置结果 Page 上源 Page 内容的宽度。 |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 获取或设置结果 Page 的左侧边距。 |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 获取或设置结果 Page 的右侧边距。 |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 获取或设置结果 Page 的顶部边距。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 创建具有指定内容尺寸的调整大小参数。 |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 创建内容尺寸以初始 Page 尺寸百分比指定的调整大小参数。边距会自动计算。 |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 创建使用指定边距值的调整大小参数。内容尺寸会自动计算。 |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | 创建调整大小参数。边距以初始 Page 尺寸的百分比指定。 |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | 创建 Page 调整大小的参数。 |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | 创建 Page 调整大小的参数。新尺寸以百分比指定。 |

### 另请参见

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


