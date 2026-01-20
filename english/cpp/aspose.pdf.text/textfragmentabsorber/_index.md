---
title: Aspose::Pdf::Text::TextFragmentAbsorber class
linktitle: TextFragmentAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentAbsorber class. Represents an absorber object of text fragments. Performs text search and provides access to search results via TextFragmentAbsorber::TextFragments collection in C++.'
type: docs
weight: 4400
url: /cpp/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class


Represents an absorber object of text fragments. Performs text search and provides access to search results via [TextFragmentAbsorber::TextFragments](../) collection.

```cpp
class TextFragmentAbsorber : public Aspose::Pdf::Text::TextAbsorber
```

## Methods

| Method | Description |
| --- | --- |
| [ApplyForAllFragments](./applyforallfragments/)(System::SharedPtr\<Font\>) | Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](./applyforallfragments/)(float) | Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](./applyforallfragments/)(System::SharedPtr\<Font\>, float) | Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [get_Errors](./get_errors/)() | List of [TextExtractionError](../textextractionerror/) objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [get_ExtractionOptions](./get_extractionoptions/)() override | Gets text extraction options. |
| [get_HasErrors](./get_haserrors/)() | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [get_Phrase](./get_phrase/)() const | Gets phrase that the [TextFragmentAbsorber](./) searches on the PDF document or page. |
| [get_RegexResults](./get_regexresults/)() const | Gets dictionary of search occurrences that are presented with [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/) class as key and [TextFragment](../textfragment/) as value. |
| [get_Text](./get_text/)() override | Gets extracted text that the [TextAbsorber](../textabsorber/) extracts on the PDF document or page. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Gets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [get_TextFragments](./get_textfragments/)() | Gets collection of search occurrences that are presented with [TextFragment](../textfragment/) objects. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [get_TextSearchOptions](./get_textsearchoptions/)() override | Gets search options. The options enable search using regular expressions. |
| [RemoveAllText](./removealltext/)(System::SharedPtr\<Page\>) | Removes all text from the specified page. |
| [RemoveAllText](./removealltext/)(System::SharedPtr\<Page\>, System::SharedPtr\<Rectangle\>) | Removes text inside the specified rectangle from the specified page. |
| [RemoveAllText](./removealltext/)(System::SharedPtr\<Document\>) | Removes all text from the document. |
| [Reset](./reset/)() | Clears TextFragments collection of this [TextFragmentAbsorber](./) object. |
| [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) override | Sets text extraction options. |
| [set_Phrase](./set_phrase/)(System::String) | Sets phrase that the [TextFragmentAbsorber](./) searches on the PDF document or page. |
| [set_TextEditOptions](./set_texteditoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [set_TextFragments](./set_textfragments/)(System::SharedPtr\<TextFragmentCollection\>) | Gets collection of search occurrences that are presented with [TextFragment](../textfragment/) objects. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>) | Sets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) override | Sets search options. The options enable search using regular expressions. |
| [TextFragmentAbsorber](./textfragmentabsorber/)() | Initializes a new instance of the [TextFragmentAbsorber](./) that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) with text edit options, that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::String) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::SharedPtr\<System::Text::RegularExpressions::Regex\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/) class object. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase, text search options and text edit options. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Initializes a new instance of the [TextFragmentAbsorber](./) class for the specified text phrase and text edit options. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) override | Performs search on the specified page. |
| [Visit](./visit/)(System::SharedPtr\<Document\>) override | Performs search on the specified document. |
| [Visit](./visit/)(System::SharedPtr\<XForm\>) override | Performs search on the specified form object. |
## Remarks


The [TextFragmentAbsorber](./) object is basically used in text search scenario. When the search is completed the occurrences are represented with [TextFragment](../textfragment/) objects that the [TextFragmentAbsorber::TextFragments](../) collection contains. The [TextFragment](../textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). 
## See Also

* Class [TextAbsorber](../textabsorber/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
