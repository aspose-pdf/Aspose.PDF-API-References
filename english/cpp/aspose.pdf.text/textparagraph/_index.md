---
title: Aspose::Pdf::Text::TextParagraph class
linktitle: TextParagraph
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextParagraph class. Represents text paragraphs as multiline text object in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf.text/textparagraph/
---
## TextParagraph class


Represents text paragraphs as multiline text object.

```cpp
class TextParagraph : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AppendLine](./appendline/)(System::String) | Appends text line. |
| [AppendLine](./appendline/)(System::String, float) | Appends text line. |
| [AppendLine](./appendline/)(System::String, System::SharedPtr\<TextState\>) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(System::String, System::SharedPtr\<TextState\>, float) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(System::SharedPtr\<TextFragment\>) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(System::SharedPtr\<TextFragment\>, System::SharedPtr\<TextState\>) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(System::SharedPtr\<TextFragment\>, System::SharedPtr\<TextState\>, float) | Appends text line with text state parameters. |
| [BeginEdit](./beginedit/)() | Begins the editing of the [TextParagraph](./). |
| [EndEdit](./endedit/)() | Ends the editing of the [TextParagraph](./). |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Gets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [get_FormattingOptions](./get_formattingoptions/)() const | Gets formatting options. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Gets horizontal alignment for the text inside paragrph's [Rectangle](../../aspose.pdf/rectangle/). |
| [get_Justify](./get_justify/)() | Gets value whether text is justified. |
| [get_Margin](./get_margin/)() const | Gets the padding. |
| [get_Position](./get_position/)() const | Gets position of the paragraph. |
| [get_Rectangle](./get_rectangle/)() const | Gets rectangle of the paragraph. |
| [get_Rotation](./get_rotation/)() const | Gets rotation angle in degrees. |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Gets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [get_TextRectangle](./get_textrectangle/)() | Gets rectangle of the text placed to the paragraph. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Gets vertical alignment for the text inside paragrph's [Rectangle](../../aspose.pdf/rectangle/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [set_FormattingOptions](./set_formattingoptions/)(System::SharedPtr\<TextFormattingOptions\>) | Sets formatting options. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets horizontal alignment for the text inside paragrph's [Rectangle](../../aspose.pdf/rectangle/). |
| [set_Justify](./set_justify/)(bool) | Sets value whether text is justified. |
| [set_Margin](./set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets the padding. |
| [set_Position](./set_position/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Sets position of the paragraph. |
| [set_Rectangle](./set_rectangle/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets rectangle of the paragraph. |
| [set_Rotation](./set_rotation/)(double) | Sets rotation angle in degrees. |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets vertical alignment for the text inside paragrph's [Rectangle](../../aspose.pdf/rectangle/). |
| [TextParagraph](./textparagraph/)() | Creates [TextParagraph](./) object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
