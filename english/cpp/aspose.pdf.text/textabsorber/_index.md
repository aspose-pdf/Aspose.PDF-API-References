---
title: Aspose::Pdf::Text::TextAbsorber class
linktitle: TextAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextAbsorber class. Represents an absorber object of a text. Performs text extraction and provides access to the result via TextAbsorber::Text object in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.text/textabsorber/
---
## TextAbsorber class


Represents an absorber object of a text. Performs text extraction and provides access to the result via [TextAbsorber::Text](../) object.

```cpp
class TextAbsorber : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Errors](./get_errors/)() const | List of [TextExtractionError](../textextractionerror/) objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| virtual [get_ExtractionOptions](./get_extractionoptions/)() | Gets text extraction options. |
| [get_HasErrors](./get_haserrors/)() const | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| virtual [get_Text](./get_text/)() | Gets extracted text that the [TextAbsorber](./) extracts on the PDF document or page. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Gets text search options. |
| virtual [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) | Sets text extraction options. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Sets text search options. |
| [TextAbsorber](./textabsorber/)() | Initializes a new instance of the [TextAbsorber](./). |
| [TextAbsorber](./textabsorber/)(System::SharedPtr\<TextExtractionOptions\>) | Initializes a new instance of the [TextAbsorber](./) with extraction options. |
| [TextAbsorber](./textabsorber/)(System::SharedPtr\<TextExtractionOptions\>, System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TextAbsorber](./) with extraction and text search options. |
| [TextAbsorber](./textabsorber/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Initializes a new instance of the [TextAbsorber](./) with text search options. |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extracts text on the specified page. |
| virtual [Visit](./visit/)(System::SharedPtr\<XForm\>) | Extracts text on the specified [XForm](../../aspose.pdf/xform/). |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>) | Extracts text on the specified document. |
## Remarks


The [TextAbsorber](./) object is used to extract text from a [Pdf](../../aspose.pdf/) document or the document's page. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
