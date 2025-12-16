---
title: Aspose::Pdf::Text::TextParagraphAbsorber class
linktitle: TextParagraphAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextParagraphAbsorber class. Represents an absorber object of text paragraphs. Performs text search and provides access to search results via TextParagraphAbsorber::TextParagraphs collection in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.text/textparagraphabsorber/
---
## TextParagraphAbsorber class


Represents an absorber object of text paragraphs. Performs text search and provides access to search results via [TextParagraphAbsorber::TextParagraphs](../) collection.

```cpp
class TextParagraphAbsorber : public Aspose::Pdf::Text::TextAbsorber
```

## Methods

| Method | Description |
| --- | --- |
| [get_Rectangles](./get_rectangles/)() const | Gets ractangles that the [TextParagraphAbsorber](./) used to searche for text paragraphs on the PDF document or page. |
| [get_TextParagraphs](./get_textparagraphs/)() const | Gets collection of search occurrences that are presented with [TextParagraph](../textparagraph/) objects. |
| [set_Rectangles](./set_rectangles/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Sets ractangles that the [TextParagraphAbsorber](./) used to searche for text paragraphs on the PDF document or page. |
| [set_TextParagraphs](./set_textparagraphs/)(System::SharedPtr\<TextParagraphCollection\>) | Gets collection of search occurrences that are presented with [TextParagraph](../textparagraph/) objects. |
| [TextParagraphAbsorber](./textparagraphabsorber/)(System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Initializes a new instance of the [TextParagraphAbsorber](./) with rectangles collection. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) override | Performs search on the specified page. |
## See Also

* Class [TextAbsorber](../textabsorber/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
