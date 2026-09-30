---
title: "PdfFileEditor.ContentsResizeParameters Class"
linktitle: "PdfFileEditor.ContentsResizeParameters"
articleTitle: "PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileEditor.ContentsResizeParameters class. Class for specifing page resize parameters. Allow to set the following parameters: Size of r..."
type: docs
weight: 360
url: "/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/"
keywords: "PdfFileEditor.ContentsResizeParameters, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileEditor.ContentsResizeParameters class

Class for specifing page resize parameters.
 Allow to set the following parameters: 
 Size of result page (width, height) in default space units or in percents of initial pages size; 
 Left, Top, Bottom and Right margins in default space units or in percents of initial page size;
 Some values may be left null for automatic calculation. These values will be calculated 
 from rest of page size after calculation explicitly specified values.
 For example: if page width = 100 and new page width specified 60 units then 
 left and right margins are automatically calculated:
 (100 - 60) / 2 = 15.
 This class is used in ResizeContents method.

```csharp
public class ContentsResizeParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentsResizeParameters](./contentsresizeparameters/#constructor)() | Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required. |
| [ContentsResizeParameters](./contentsresizeparameters/#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Creates resize parameters with specified margin values and contents size. |

## Properties

| Name | Description |
| --- | --- |
| [BottomMargin](./bottommargin/) { get; set; } | Gets or sets bottom margin on the resultant page. |
| [ChangeMediaBox](./changemediabox/) { get; set; } | Gets and sets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is `false` |
| [ContentsHeight](./contentsheight/) { get; set; } | Gets or sets height of the content of the source page on the resultant page. |
| [ContentsWidth](./contentswidth/) { get; set; } | Gets or sets width of the content of the source page on the resultant page. |
| [LeftMargin](./leftmargin/) { get; set; } | Gets or sets left margin on the resultant page. |
| [RightMargin](./rightmargin/) { get; set; } | Gets or sets right margin on the resultant page. |
| [TopMargin](./topmargin/) { get; set; } | Gets or sets top margin on the resultant page. |

## Methods

| Name | Description |
| --- | --- |
| static [ContentSize](./contentsize/)(double, double) | Creates resize parameters with specified contents size. |
| static [ContentSizePercent](./contentsizepercent/)(double, double) | Creates resize parameters with specified contents size in percents of initial page size. Margins are caculated automatically. |
| static [Margins](./margins/)(double, double, double, double) | Creates resize parameters with specifed margins value. Contents size is automatically calculated. |
| static [MarginsPercent](./marginspercent/)(double, double, double, double) | Creates resize parameters. Margins are specified in percents of initial page size. |
| static [PageResize](./pageresize/)(double, double) | Creates resize paramters for page resize. |
| static [PageResizePct](./pageresizepct/)(double, double) | Creates resize paramters for page resize. New sizes are specified in percent. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

