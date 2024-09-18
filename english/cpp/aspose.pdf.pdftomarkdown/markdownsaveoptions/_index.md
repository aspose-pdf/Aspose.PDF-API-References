---
title: Aspose::Pdf::PdfToMarkdown::MarkdownSaveOptions class
linktitle: MarkdownSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfToMarkdown::MarkdownSaveOptions class. Represents the document save option class in the markdown format in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.pdftomarkdown/markdownsaveoptions/
---
## MarkdownSaveOptions class


Represents the document save option class in the markdown format.

```cpp
class MarkdownSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_AreaToExtract](./get_areatoextract/)() const | Get or set an rectangle area to extract content to markdown. |
| [get_CacheGlyphs](../../aspose.pdf/saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../../aspose.pdf/saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_EmphasisStyle](./get_emphasisstyle/)() const | Gets the style of emphasis for generated document. |
| [get_ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_ExtractVectorGraphics](./get_extractvectorgraphics/)() const | Gets and sets a property indicating whether vector graphics should be extracted. |
| [get_HeadingLevels](./get_headinglevels/)() const | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition [PdfToMarkdown::HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategy will be selected when set [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../headingrecognitionstrategy/) strategies even if the document contains bookmarks. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Gets the heading recognition strategy. |
| [get_HeadingStyle](./get_headingstyle/)() const | Gets the heading style for generated document. |
| [get_LineBreakStyle](./get_linebreakstyle/)() const | Gets the line break style for generated document. |
| [get_ResourcesDirectoryName](./get_resourcesdirectoryname/)() const | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [get_SaveFormat](../../aspose.pdf/saveoptions/get_saveformat/)() const | Format of data save. |
| [get_SubscriptAndSuperscriptConversion](./get_subscriptandsuperscriptconversion/)() const | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [get_UseImageHtmlTag](./get_useimagehtmltag/)() const | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |
| [get_WarningHandler](../../aspose.pdf/saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Creates an instance option to save a document in markdown format. |
| [set_AreaToExtract](./set_areatoextract/)(System::SharedPtr\<Rectangle\>) | Get or set an rectangle area to extract content to markdown. |
| [set_CacheGlyphs](../../aspose.pdf/saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../../aspose.pdf/saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_EmphasisStyle](./set_emphasisstyle/)(Aspose::Pdf::PdfToMarkdown::EmphasisStyle) | Sets the style of emphasis for generated document. |
| [set_ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_ExtractVectorGraphics](./set_extractvectorgraphics/)(bool) | Gets and sets a property indicating whether vector graphics should be extracted. |
| [set_HeadingLevels](./set_headinglevels/)(System::SharedPtr\<Aspose::Pdf::PdfToMarkdown::HeadingLevels\>) | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition [PdfToMarkdown::HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategy will be selected when set [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../headingrecognitionstrategy/) strategies even if the document contains bookmarks. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::PdfToMarkdown::HeadingRecognitionStrategy) | Sets the heading recognition strategy. |
| [set_HeadingStyle](./set_headingstyle/)(Aspose::Pdf::PdfToMarkdown::HeadingStyle) | Sets the heading style for generated document. |
| [set_LineBreakStyle](./set_linebreakstyle/)(Aspose::Pdf::PdfToMarkdown::LineBreakStyle) | Sets the line break style for generated document. |
| [set_ResourcesDirectoryName](./set_resourcesdirectoryname/)(System::String) | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [set_SubscriptAndSuperscriptConversion](./set_subscriptandsuperscriptconversion/)(bool) | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [set_UseImageHtmlTag](./set_useimagehtmltag/)(bool) | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |
| [set_WarningHandler](../../aspose.pdf/saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [UnifiedSaveOptions](../../aspose.pdf/unifiedsaveoptions/unifiedsaveoptions/)() |  |
## See Also

* Class [UnifiedSaveOptions](../../aspose.pdf/unifiedsaveoptions/)
* Namespace [Aspose::Pdf::PdfToMarkdown](../)
* Library [Aspose.PDF for C++](../../)
