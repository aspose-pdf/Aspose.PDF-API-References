---
title: Aspose::Pdf::Text::TextSegment class
linktitle: TextSegment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextSegment class. Represents segment of Pdf text in C++.'
type: docs
weight: 5300
url: /cpp/aspose.pdf.text/textsegment/
---
## TextSegment class


Represents segment of [Pdf](../../aspose.pdf/) text.

```cpp
class TextSegment : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaselinePosition](./get_baselineposition/)() const | Gets text position for text, represented with [TextSegment](./) object. The YIndent of the [Position](../position/) structure represents baseline coordinate of the text segment. |
| [get_Characters](./get_characters/)() | Gets collection of [CharInfo](../charinfo/) objects that represent information on characters in the text segment. |
| [get_EndCharIndex](./get_endcharindex/)() const | Gets ending character index of current segment in the show text operator (Tj, TJ) segment. |
| [get_Hyperlink](./get_hyperlink/)() const | Gets the segment hyperlink(for pdf generator). |
| [get_Position](./get_position/)() const | Gets text position for text, represented with [TextSegment](./) object. |
| [get_Rectangle](./get_rectangle/)() | Gets rectangle of the [TextSegment](./). |
| [get_StartCharIndex](./get_startcharindex/)() const | Gets starting character index of current segment in the show text operator (Tj, TJ) segment. |
| [get_Text](./get_text/)() const | Gets [System::String](../../system/string/) text object that the [TextSegment](./) object represents. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Gets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [get_TextState](./get_textstate/)() const | Gets text state for the text that [TextSegment](./) object represents. |
| static [MyHtmlEncode](./myhtmlencode/)(System::String) | Encodes string as html. |
| [set_BaselinePosition](./set_baselineposition/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Gets text position for text, represented with [TextSegment](./) object. The YIndent of the [Position](../position/) structure represents baseline coordinate of the text segment. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the segment hyperlink(for pdf generator). |
| [set_Position](./set_position/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Gets text position for text, represented with [TextSegment](./) object. |
| [set_Text](./set_text/)(System::String) | Sets [System::String](../../system/string/) text object that the [TextSegment](./) object represents. |
| [set_TextEditOptions](./set_texteditoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [set_TextState](./set_textstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Sets text state for the text that [TextSegment](./) object represents. |
| [TextSegment](./textsegment/)() | Creates [TextSegment](./) object. |
| [TextSegment](./textsegment/)(System::String) | Creates [TextSegment](./) object. |
## Remarks


In a few words, [TextSegment](./) objects are children of [TextFragment](../textfragment/) object.

In details:

[Text](../) of pdf document in [Aspose::Pdf](../../aspose.pdf/) is represented by two basic objects: [TextFragment](../textfragment/) and [TextSegment](./)

The differences between them is mostly context-dependent.

Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. 
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
 Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments.

The [Aspose.Pdf](../../aspose.pdf/) text model basically establishes that [TextFragment](../textfragment/) object provides single logic operation set over physical [TextSegment](./) objects set that represent user's query.

In text search scenario, [TextFragment](../textfragment/) is logical "hello world" text representation, and [TextSegment](./) object collection represents all physical segments that construct "hello world" text object.

So, [TextFragment](../textfragment/) is close to logical text representation. And [TextSegment](./) is close to physical text representation.

Obviously each [TextSegment](./) object may have it's own font, coloring, positioning properties.

[TextFragment](../textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](./) objects are accessible and users are able to operate with [TextSegment](./) objects independently. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
