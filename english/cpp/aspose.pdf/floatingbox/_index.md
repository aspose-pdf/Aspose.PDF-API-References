---
title: Aspose::Pdf::FloatingBox class
linktitle: FloatingBox
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FloatingBox class. Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf/floatingbox/
---
## FloatingBox class


Represents a [FloatingBox](./) in a [Pdf](../) document. [FloatingBox](./) is custom positioned.

```cpp
class FloatingBox : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../baseparagraph/baseparagraph/)() |  |
| [Clone](./clone/)() override | Clones a new [FloatingBox](./) object. [Paragraphs](../paragraphs/) in the floating box are not cloned. |
| [FloatingBox](./floatingbox/)(float, float) | Initializes a new instance of the [FloatingBox](./) class with specified width and height. |
| [FloatingBox](./floatingbox/)() | Initializes a new instance of the [FloatingBox](./) class. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets a [Aspose::Pdf::Color](../color/) object that indicates the background color of the floating box. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Gets background image for page (for generator only, not filled in when reading document). |
| [get_Border](./get_border/)() const | Gets a [BorderInfo](../borderinfo/) object that indicates the border info of the floating box. |
| [get_ColumnInfo](./get_columninfo/)() const | Gets a column info. |
| [get_Height](./get_height/)() const | Gets a float value that indicates the height of the floating box. |
| virtual [get_HorizontalAlignment](../baseparagraph/get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](../baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_IsNeedRepeating](./get_isneedrepeating/)() const | Gets a bool value that indicates whether the paragraph need to be repeated on next page. Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [get_Left](./get_left/)() const | Gets the table left coordinate. |
| [get_Margin](../baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Padding](./get_padding/)() const | Gets a [MarginInfo](../margininfo/) object that indicates the padding of the floating box. |
| [get_Paragraphs](./get_paragraphs/)() const | Gets a [Paragraphs](../paragraphs/) collection that indicates all paragraphs in the cell. |
| [get_Top](./get_top/)() const | Gets the table top coordinate. |
| virtual [get_VerticalAlignment](../baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_Width](./get_width/)() const | Gets a float value that indicates the width of the floating box. |
| [get_ZIndex](../baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets a [Aspose::Pdf::Color](../color/) object that indicates the background color of the floating box. |
| [set_BackgroundImage](./set_backgroundimage/)(System::SharedPtr\<Image\>) | Sets background image for page (for generator only, not filled in when reading document). |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets a [BorderInfo](../borderinfo/) object that indicates the border info of the floating box. |
| [set_ColumnInfo](./set_columninfo/)(System::SharedPtr\<Aspose::Pdf::ColumnInfo\>) | Sets a column info. |
| [set_Height](./set_height/)(double) | Sets a float value that indicates the height of the floating box. |
| virtual [set_HorizontalAlignment](../baseparagraph/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](../baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_IsNeedRepeating](./set_isneedrepeating/)(bool) | Sets a bool value that indicates whether the paragraph need to be repeated on next page. Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [set_Left](./set_left/)(double) | Sets the table left coordinate. |
| [set_Margin](../baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Padding](./set_padding/)(System::SharedPtr\<MarginInfo\>) | Sets a [MarginInfo](../margininfo/) object that indicates the padding of the floating box. |
| [set_Paragraphs](./set_paragraphs/)(System::SharedPtr\<Aspose::Pdf::Paragraphs\>) | Sets a [Paragraphs](../paragraphs/) collection that indicates all paragraphs in the cell. |
| [set_Top](./set_top/)(double) | Sets the table top coordinate. |
| virtual [set_VerticalAlignment](../baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_Width](./set_width/)(double) | Sets a float value that indicates the width of the floating box. |
| [set_ZIndex](../baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
