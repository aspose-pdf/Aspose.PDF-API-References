---
title: Aspose::Pdf::Heading class
linktitle: Heading
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Heading class. Represents heading in C++.'
type: docs
weight: 5500
url: /cpp/aspose.pdf/heading/
---
## Heading class


Represents heading.

```cpp
class Heading : public Aspose::Pdf::Text::TextFragment
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../baseparagraph/baseparagraph/)() |  |
| [Clone](./clone/)() override | Clone the heading. |
| [CloneWithSegments](./clonewithsegments/)() override | Clone the heading with all segments. |
| [get_BaselinePosition](../../aspose.pdf.text/textfragment/get_baselineposition/)() | Gets text position for text, represented with [TextFragment](../../aspose.pdf.text/textfragment/) object. The YIndent of the [Position](../../aspose.pdf.text/position/) structure represents baseline coordinate of the text fragment. |
| [get_DestinationPage](./get_destinationpage/)() const | Gets the destination page. |
| [get_EndNote](../../aspose.pdf.text/textfragment/get_endnote/)() const | Gets the paragraph end note.(for pdf generation only) |
| [get_FootNote](../../aspose.pdf.text/textfragment/get_footnote/)() const | Gets the paragraph foot note.(for pdf generation only) |
| [get_Form](../../aspose.pdf.text/textfragment/get_form/)() const | Gets form object that contains the [TextFragment](../../aspose.pdf.text/textfragment/). |
| [get_HorizontalAlignment](../../aspose.pdf.text/textfragment/get_horizontalalignment/)() override | Gets a horizontal alignment of text fragment. |
| virtual [get_Hyperlink](../baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsAutoSequence](./get_isautosequence/)() const | Gets the heading should be numered automatically. |
| [get_IsFirstParagraphInColumn](../baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInList](./get_isinlist/)() const | Gets the heading should be in toc list. |
| [get_IsInNewPage](../baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Level](./get_level/)() const | Gets the level. |
| [get_Margin](../baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Page](../../aspose.pdf.text/textfragment/get_page/)() const | Gets page that contains the [TextFragment](../../aspose.pdf.text/textfragment/). |
| [get_Position](../../aspose.pdf.text/textfragment/get_position/)() | Gets text position for text, represented with [TextFragment](../../aspose.pdf.text/textfragment/) object. |
| [get_Rectangle](../../aspose.pdf.text/textfragment/get_rectangle/)() | Gets rectangle of the [TextFragment](../../aspose.pdf.text/textfragment/). |
| [get_ReplaceOptions](../../aspose.pdf.text/textfragment/get_replaceoptions/)() const | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [get_Segments](../../aspose.pdf.text/textfragment/get_segments/)() const | Gets text segments for current [TextFragment](../../aspose.pdf.text/textfragment/). |
| [get_StartNumber](./get_startnumber/)() const | Gets the heading start number. |
| [get_Style](./get_style/)() const | Gets style. |
| [get_Text](../../aspose.pdf.text/textfragment/get_text/)() | Gets **System::String** text object that the [TextFragment](../../aspose.pdf.text/textfragment/) object represents. |
| [get_TextState](../../aspose.pdf.text/textfragment/get_textstate/)() | Gets text state for the text that [TextFragment](../../aspose.pdf.text/textfragment/) object represents. |
| [get_TocPage](./get_tocpage/)() const | Gets the page that contains this heading. |
| [get_Top](./get_top/)() const | Gets the top Y of this headings. |
| [get_UserLabel](./get_userlabel/)() const | Gets user label. |
| [get_VerticalAlignment](../../aspose.pdf.text/textfragment/get_verticalalignment/)() override | Gets a vertical alignment of text fragment. |
| [get_WrapLinesCount](../../aspose.pdf.text/textfragment/get_wraplinescount/)() const | Gets wrap lines count for this paragraph(for pdf generation only) |
| [get_ZIndex](../baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [Heading](./heading/)(int32_t) | Initializes a new instance of the [Cell](../cell/) class. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int32_t, int32_t) | Gets [TextSegment](../../aspose.pdf.text/textsegment/)(s) representing specified part of the [TextFragment](../../aspose.pdf.text/textfragment/) text. |
| [set_BaselinePosition](../../aspose.pdf.text/textfragment/set_baselineposition/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Gets text position for text, represented with [TextFragment](../../aspose.pdf.text/textfragment/) object. The YIndent of the [Position](../../aspose.pdf.text/position/) structure represents baseline coordinate of the text fragment. |
| [set_DestinationPage](./set_destinationpage/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Gets the destination page. |
| [set_EndNote](../../aspose.pdf.text/textfragment/set_endnote/)(System::SharedPtr\<Note\>) | Sets the paragraph end note.(for pdf generation only) |
| [set_FootNote](../../aspose.pdf.text/textfragment/set_footnote/)(System::SharedPtr\<Note\>) | Sets the paragraph foot note.(for pdf generation only) |
| [set_HorizontalAlignment](../../aspose.pdf.text/textfragment/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets a horizontal alignment of text fragment. |
| [set_Hyperlink](../../aspose.pdf.text/textfragment/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) override | Sets the fragment hyperlink. |
| [set_IsAutoSequence](./set_isautosequence/)(bool) | Gets the heading should be numered automatically. |
| [set_IsFirstParagraphInColumn](../baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInList](./set_isinlist/)(bool) | Gets the heading should be in toc list. |
| [set_IsInNewPage](../baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Level](./set_level/)(int32_t) | Gets the level. |
| [set_Margin](../baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Position](../../aspose.pdf.text/textfragment/set_position/)(System::SharedPtr\<Aspose::Pdf::Text::Position\>) | Sets text position for text, represented with [TextFragment](../../aspose.pdf.text/textfragment/) object. |
| [set_Segments](../../aspose.pdf.text/textfragment/set_segments/)(System::SharedPtr\<TextSegmentCollection\>) | Gets text segments for current [TextFragment](../../aspose.pdf.text/textfragment/). |
| [set_StartNumber](./set_startnumber/)(int32_t) | Gets the heading start number. |
| [set_Style](./set_style/)(NumberingStyle) | Sets style. |
| [set_Text](../../aspose.pdf.text/textfragment/set_text/)(System::String) | Sets **System::String** text object that the [TextFragment](../../aspose.pdf.text/textfragment/) object represents. |
| [set_TocPage](./set_tocpage/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Gets the page that contains this heading. |
| [set_Top](./set_top/)(double) | Gets the top Y of this headings. |
| [set_UserLabel](./set_userlabel/)(System::SharedPtr\<Text::TextSegment\>) | Sets user label. |
| [set_VerticalAlignment](../../aspose.pdf.text/textfragment/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) override | Sets a vertical alignment of text fragment. |
| [set_WrapLinesCount](../../aspose.pdf.text/textfragment/set_wraplinescount/)(int32_t) | Sets wrap lines count for this paragraph(for pdf generation only) |
| [set_ZIndex](../baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [TextFragment](../../aspose.pdf.text/textfragment/textfragment/)() | Initializes new instance of the [TextFragment](../../aspose.pdf.text/textfragment/) object. |
| [TextFragment](../../aspose.pdf.text/textfragment/textfragment/)(System::SharedPtr\<TabStops\>) | Initializes new instance of the [TextFragment](../../aspose.pdf.text/textfragment/) object with predefined [TabStops](../../aspose.pdf.text/tabstops/) positions. |
| [TextFragment](../../aspose.pdf.text/textfragment/textfragment/)(System::String) | Creates [TextFragment](../../aspose.pdf.text/textfragment/) object with single [TextSegment](../../aspose.pdf.text/textsegment/) object inside. Specifies text string inside the segment. |
| [TextFragment](../../aspose.pdf.text/textfragment/textfragment/)(System::String, System::SharedPtr\<TabStops\>) | Creates [TextFragment](../../aspose.pdf.text/textfragment/) object with single [TextSegment](../../aspose.pdf.text/textsegment/) object inside and predefined [TabStops](../../aspose.pdf.text/tabstops/) positions. |
## See Also

* Class [TextFragment](../../aspose.pdf.text/textfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
