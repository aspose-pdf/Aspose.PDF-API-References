---
title: Aspose::Pdf::Text::TextFragment class
linktitle: TextFragment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragment class. Represents fragment of Pdf text in C++.'
type: docs
weight: 4300
url: /cpp/aspose.pdf.text/textfragment/
---
## TextFragment class


Represents fragment of [Pdf](../../aspose.pdf/) text.

```cpp
class TextFragment : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clone the fragment. |
| virtual [CloneWithSegments](./clonewithsegments/)() | Clone the fragment with all segments. |
| [get_BaselinePosition](./get_baselineposition/)() | Gets text position for text, represented with [TextFragment](./) object. The YIndent of the [Position](../position/) structure represents baseline coordinate of the text fragment. |
| [get_EndNote](./get_endnote/)() const | Gets the paragraph end note.(for pdf generation only) |
| [get_FootNote](./get_footnote/)() const | Gets the paragraph foot note.(for pdf generation only) |
| [get_Form](./get_form/)() const | Gets form object that contains the [TextFragment](./). |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Gets a horizontal alignment of text fragment. |
| [get_Page](./get_page/)() const | Gets page that contains the [TextFragment](./). |
| [get_Position](./get_position/)() | Gets text position for text, represented with [TextFragment](./) object. |
| [get_Rectangle](./get_rectangle/)() | Gets rectangle of the [TextFragment](./). |
| [get_ReplaceOptions](./get_replaceoptions/)() const | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [get_Segments](./get_segments/)() const | Gets text segments for current [TextFragment](./). |
| [get_Text](./get_text/)() | Gets [System::String](../../system/string/) text object that the [TextFragment](./) object represents. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Gets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [get_TextState](./get_textstate/)() | Gets text state for the text that [TextFragment](./) object represents. |
| [get_VerticalAlignment](./get_verticalalignment/)() override | Gets a vertical alignment of text fragment. |
| [get_WrapLinesCount](./get_wraplinescount/)() const | Gets wrap lines count for this paragraph(for pdf generation only) |
| [IsolateTextSegments](./isolatetextsegments/)(int32_t, int32_t) | Gets [TextSegment](../textsegment/)(s) representing specified part of the [TextFragment](./) text. |
| [set_BaselinePosition](./set_baselineposition/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Gets text position for text, represented with [TextFragment](./) object. The YIndent of the [Position](../position/) structure represents baseline coordinate of the text fragment. |
| [set_EndNote](./set_endnote/)(System::SharedPtr\<Note\>) | Sets the paragraph end note.(for pdf generation only) |
| [set_FootNote](./set_footnote/)(System::SharedPtr\<Note\>) | Sets the paragraph foot note.(for pdf generation only) |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets a horizontal alignment of text fragment. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) override | Sets the fragment hyperlink. |
| [set_Position](./set_position/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Sets text position for text, represented with [TextFragment](./) object. |
| [set_Segments](./set_segments/)(System::SharedPtr\<TextSegmentCollection\>) | Gets text segments for current [TextFragment](./). |
| [set_Text](./set_text/)(System::String) | Sets [System::String](../../system/string/) text object that the [TextFragment](./) object represents. |
| [set_TextEditOptions](./set_texteditoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) override | Sets a vertical alignment of text fragment. |
| [set_WrapLinesCount](./set_wraplinescount/)(int32_t) | Sets wrap lines count for this paragraph(for pdf generation only) |
| [TextFragment](./textfragment/)() | Initializes new instance of the [TextFragment](./) object. |
| [TextFragment](./textfragment/)(System::SharedPtr\<TabStops\>) | Initializes new instance of the [TextFragment](./) object with predefined [TabStops](../tabstops/) positions. |
| [TextFragment](./textfragment/)(System::String) | Creates [TextFragment](./) object with single [TextSegment](../textsegment/) object inside. Specifies text string inside the segment. |
| [TextFragment](./textfragment/)(System::String, System::SharedPtr\<TabStops\>) | Creates [TextFragment](./) object with single [TextSegment](../textsegment/) object inside and predefined [TabStops](../tabstops/) positions. |
## Remarks


In a few words, [TextFragment](./) object contains list of [TextSegment](../textsegment/) objects.

In details: [Text](../) of pdf document in [Aspose::Pdf](../../aspose.pdf/) is represented by two basic objects: [TextFragment](./) and [TextSegment](../textsegment/)

The differences between them is mostly context-dependent.

Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. 
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
 Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments.

The [Aspose.Pdf](../../aspose.pdf/) text model basically establishes that [TextFragment](./) object provides single logic operation set over physical [TextSegment](../textsegment/) objects set that represent user's query.

In text search scenario, [TextFragment](./) is logical "hello world" text representation, and [TextSegment](../textsegment/) object collection represents all physical segments that construct "hello world" text object.

So, [TextFragment](./) is close to logical text representation. And [TextSegment](../textsegment/) is close to physical text representation.

Obviously each [TextSegment](../textsegment/) object may have it's own font, coloring, positioning properties.

[TextFragment](./) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](../textsegment/) objects are accessible and users are able to operate with [TextSegment](../textsegment/) objects independently.

[Note](../../aspose.pdf/note/) that changing [TextFragment](./) properties may change inner [Segments](../) collection because [TextFragment](./) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [Segments](../) collection unchanged, please change inner segments individually. 
## See Also

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
