---
title: Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters class
linktitle: ContentsResizeParameters
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters class. Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method in C++.'
type: docs
weight: 7300
url: /cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/
---
## ContentsResizeParameters class


Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; [Left](../../../aspose.pdf/left/), Top, Bottom and [Right](../../../aspose.pdf/right/) margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method.

```cpp
class ContentsResizeParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [ContentSize](./contentsize/)(double, double) | Creates resize parameters with specified contents size. |
| static [ContentSizePercent](./contentsizepercent/)(double, double) | Creates resize parameters with specified contents size in percents of initial page size. Margins are caculated automatically. |
| [ContentsResizeParameters](./contentsresizeparameters/)() | Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required. |
| [ContentsResizeParameters](./contentsresizeparameters/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>, System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>, System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>, System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>, System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>, System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Creates resize parameters with specified margin values and contents size. |
| [get_BottomMargin](./get_bottommargin/)() const | Gets bottom margin on the resultant page. |
| [get_ChangeMediaBox](./get_changemediabox/)() const | Gets and sets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is **false** |
| [get_ContentsHeight](./get_contentsheight/)() const | Gets height of the content of the source page on the resultant page. |
| [get_ContentsWidth](./get_contentswidth/)() const | Gets width of the content of the source page on the resultant page. |
| [get_LeftMargin](./get_leftmargin/)() const | Gets left margin on the resultant page. |
| [get_RightMargin](./get_rightmargin/)() const | Gets right margin on the resultant page. |
| [get_TopMargin](./get_topmargin/)() const | Gets top margin on the resultant page. |
| static [Margins](./margins/)(double, double, double, double) | Creates resize parameters with specifed margins value. Contents size is automatically calculated. |
| static [MarginsPercent](./marginspercent/)(double, double, double, double) | Creates resize parameters. Margins are specified in percents of initial page size. |
| static [PageResize](./pageresize/)(double, double) | Creates resize paramters for page resize. |
| static [PageResizePct](./pageresizepct/)(double, double) | Creates resize paramters for page resize. New sizes are specified in percent. |
| [set_BottomMargin](./set_bottommargin/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets bottom margin on the resultant page. |
| [set_ChangeMediaBox](./set_changemediabox/)(bool) | Gets and sets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is **false** |
| [set_ContentsHeight](./set_contentsheight/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets height of the content of the source page on the resultant page. |
| [set_ContentsWidth](./set_contentswidth/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets width of the content of the source page on the resultant page. |
| [set_LeftMargin](./set_leftmargin/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets left margin on the resultant page. |
| [set_RightMargin](./set_rightmargin/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets right margin on the resultant page. |
| [set_TopMargin](./set_topmargin/)(System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>) | Sets top margin on the resultant page. |
## See Also

* Class [Object](../../../system/object/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
