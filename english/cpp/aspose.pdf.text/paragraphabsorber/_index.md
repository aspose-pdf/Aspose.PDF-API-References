---
title: Aspose::Pdf::Text::ParagraphAbsorber class
linktitle: ParagraphAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::ParagraphAbsorber class. Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via TextFragments collections grouped by structure elements in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class


Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via [TextFragments](../) collections grouped by structure elements.

```cpp
class ParagraphAbsorber : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsMulticolumnParagraphsAllowed](./get_ismulticolumnparagraphsallowed/)() const | Gets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [get_PageMarkups](./get_pagemarkups/)() const | Gets collection of [PageMarkup](../pagemarkup/) that were absorbed. |
| [get_ParagraphAbsorberOptions](./get_paragraphabsorberoptions/)() const | Gets the [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [get_SectionsSearchDepth](./get_sectionssearchdepth/)() const | Gets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Gets the [TextReplaceOptions](../textreplaceoptions/). |
| [ParagraphAbsorber](./paragraphabsorber/)() | Initializes a new instance of the [ParagraphAbsorber](./) that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t) | Initializes a new instance of the [ParagraphAbsorber](./) that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](./paragraphabsorber/)(System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>) | Initializes a new instance of the [ParagraphAbsorber](./) that performs search for sections/paragraphs of the document or page with the specified parameters. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t, System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>) | Initializes a new instance of the [ParagraphAbsorber](./) that performs search for sections/paragraphs of the document or page with the specified parameters. |
| [set_IsMulticolumnParagraphsAllowed](./set_ismulticolumnparagraphsallowed/)(bool) | Sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [set_ParagraphAbsorberOptions](./set_paragraphabsorberoptions/)(System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>) | Sets the [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [set_SectionsSearchDepth](./set_sectionssearchdepth/)(int32_t) | Sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>) | Sets the [TextReplaceOptions](../textreplaceoptions/). |
| [Visit](./visit/)(System::SharedPtr\<Document\>) | Performs search for sections and paragraphs on the specified [Document](../../aspose.pdf/document/). |
| [Visit](./visit/)(System::SharedPtr\<Page\>) | Performs search on the specified [Page](../../aspose.pdf/page/). |
## Remarks


When the search is completed the [ParagraphAbsorber::PageMarkups](../) collection will contains [PageMarkup](../pagemarkup/) objects that represents page structure by collections of [MarkupSection](../markupsection/) and [MarkupParagraph](../markupparagraph/). The [TextFragment](../textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
