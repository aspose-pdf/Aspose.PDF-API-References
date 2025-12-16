---
title: Aspose::Pdf::MarkdownSaveOptions class
linktitle: MarkdownSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::MarkdownSaveOptions class. Represents the document save option class in the markdown format in C++.'
type: docs
weight: 11000
url: /cpp/aspose.pdf/markdownsaveoptions/
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
| [get_EmphasisStyle](./get_emphasisstyle/)() const | Gets the style of emphasis for generated document. |
| [get_ExtractVectorGraphics](./get_extractvectorgraphics/)() const | Gets and sets a property indicating whether vector graphics should be extracted. |
| [get_HeadingLevels](./get_headinglevels/)() const | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategy will be selected when set [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) strategies even if the document contains bookmarks. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Gets the heading recognition strategy. |
| [get_HeadingStyle](./get_headingstyle/)() const | Gets the heading style for generated document. |
| [get_LineBreakStyle](./get_linebreakstyle/)() const | Gets the line break style for generated document. |
| [get_ResourcesDirectoryName](./get_resourcesdirectoryname/)() const | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [get_SubscriptAndSuperscriptConversion](./get_subscriptandsuperscriptconversion/)() const | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [get_UseImageHtmlTag](./get_useimagehtmltag/)() const | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Creates an instance option to save a document in markdown format. |
| [set_AreaToExtract](./set_areatoextract/)(System::SharedPtr\<Rectangle\>) | Get or set an rectangle area to extract content to markdown. |
| [set_EmphasisStyle](./set_emphasisstyle/)(Aspose::Pdf::EmphasisStyle) | Sets the style of emphasis for generated document. |
| [set_ExtractVectorGraphics](./set_extractvectorgraphics/)(bool) | Gets and sets a property indicating whether vector graphics should be extracted. |
| [set_HeadingLevels](./set_headinglevels/)(System::SharedPtr\<Aspose::Pdf::HeadingLevels\>) | Defines expected heading levels to use in FontSize recognition headers strategy. If this property value is set, then header recognition [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) strategy will be selected when set [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) strategies even if the document contains bookmarks. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Sets the heading recognition strategy. |
| [set_HeadingStyle](./set_headingstyle/)(Aspose::Pdf::HeadingStyle) | Sets the heading style for generated document. |
| [set_LineBreakStyle](./set_linebreakstyle/)(Aspose::Pdf::LineBreakStyle) | Sets the line break style for generated document. |
| [set_ResourcesDirectoryName](./set_resourcesdirectoryname/)(System::String) | Gets and sets the directory name to save document resources such as images. If the value is not specified, then the images will be written to the same directory as the markdown file itself. This is not path, it is only name! This directory will be automatically created in the directory with the saved markdown file. |
| [set_SubscriptAndSuperscriptConversion](./set_subscriptandsuperscriptconversion/)(bool) | Gets ans sets allowance to convert subscript and superscript. This value is true by default. |
| [set_UseImageHtmlTag](./set_useimagehtmltag/)(bool) | Gets and sets allowance to use of an img tag to insert images to the left and right of the text. In this case, in the markdown viewer, the text will wrap around the image. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
