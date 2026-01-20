---
title: Aspose::Pdf::Text::TextSearchOptions class
linktitle: TextSearchOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextSearchOptions class. Represents text search options in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class


Represents text search options.

```cpp
class TextSearchOptions : public Aspose::Pdf::Text::TextOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Gets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. [Text](../) segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception. |
| [get_IgnoreShadowText](./get_ignoreshadowtext/)() const | Gets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Gets indication that regular expression is used. |
| [get_LimitToPageBounds](./get_limittopagebounds/)() const | Gets indication that text is searched within the page bounds. |
| [get_LogTextExtractionErrors](./get_logtextextractionerrors/)() const | Gets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging. |
| [get_Rectangle](./get_rectangle/)() const | Gets rectangle that bounds the searched text. |
| [get_SearchForTextRelatedGraphics](./get_searchfortextrelatedgraphics/)() const | Gets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping. |
| [get_SearchInAnnotations](./get_searchinannotations/)() const | Gets value that permits searching for text in [Annotations](../../aspose.pdf.annotations/). true - text will be searched in [Annotations](../../aspose.pdf.annotations/). false - text in [Annotations](../../aspose.pdf.annotations/) won't be parsed by [TextFragmentAbsorber](../textfragmentabsorber/). |
| [get_StoredGraphicElementsMaxCount](./get_storedgraphicelementsmaxcount/)() const | Gets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found. |
| [get_UseFontEngineEncoding](./get_usefontengineencoding/)() const | Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. [Text](../) segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception. |
| [set_IgnoreShadowText](./set_ignoreshadowtext/)(bool) | Sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Sets indication that regular expression is used. |
| [set_LimitToPageBounds](./set_limittopagebounds/)(bool) | Sets indication that text is searched within the page bounds. |
| [set_LogTextExtractionErrors](./set_logtextextractionerrors/)(bool) | Sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging. |
| [set_Rectangle](./set_rectangle/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets rectangle that bounds the searched text. |
| [set_SearchForTextRelatedGraphics](./set_searchfortextrelatedgraphics/)(bool) | Sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping. |
| [set_SearchInAnnotations](./set_searchinannotations/)(bool) | Sets value that permits searching for text in [Annotations](../../aspose.pdf.annotations/). true - text will be searched in [Annotations](../../aspose.pdf.annotations/). false - text in [Annotations](../../aspose.pdf.annotations/) won't be parsed by [TextFragmentAbsorber](../textfragmentabsorber/). |
| [set_StoredGraphicElementsMaxCount](./set_storedgraphicelementsmaxcount/)(int32_t) | Sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found. |
| [set_UseFontEngineEncoding](./set_usefontengineencoding/)(bool) | Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [TextSearchOptions](./textsearchoptions/)(bool) | Initializes new instance of the [TextSearchOptions](./) object. Specifies regular expression usage mode. |
| [TextSearchOptions](./textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Initializes new instance of the [TextSearchOptions](./) object. Specifies rectangle that delimits the searched text. |
| [TextSearchOptions](./textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>, bool) | Initializes new instance of the [TextSearchOptions](./) object. Specifies rectangle that delimits the searched text and regular expression usage mode. |
## See Also

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
