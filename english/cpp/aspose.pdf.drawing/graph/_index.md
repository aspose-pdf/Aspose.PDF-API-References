---
title: Aspose::Pdf::Drawing::Graph class
linktitle: Graph
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Drawing::Graph class. Represents graph - graphics generator paragraph in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.drawing/graph/
---
## Graph class


Represents graph - graphics generator paragraph.

```cpp
class Graph : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| [Clone](./clone/)() override | Clone the graph. |
| [get_Border](./get_border/)() const | Gets the border. |
| [get_GraphInfo](./get_graphinfo/)() const | Gets a [GraphInfo](../../aspose.pdf/graphinfo/) object that indicates the graph info,such as color, line width,etc. |
| [get_Height](./get_height/)() const | Gets a float value that indicates the graph height. The unit is point. |
| virtual [get_HorizontalAlignment](../../aspose.pdf/baseparagraph/get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](../../aspose.pdf/baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsChangePosition](./get_ischangeposition/)() const | Gets change curret position after process paragraph.(default true) |
| [get_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../../aspose.pdf/baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../../aspose.pdf/baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../../aspose.pdf/baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Left](./get_left/)() const | Gets the table left coordinate. |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Shapes](./get_shapes/)() const | Gets a [Shapes](../) collection that indicates all shapes in the graph. |
| [get_Title](./get_title/)() const | Gets a string value that indicates the title of the graph. |
| [get_Top](./get_top/)() const | Gets the table top coordinate. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_Width](./get_width/)() const | Gets a float value that indicates the graph width. The unit is point. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [Graph](./graph/)(double, double) | Initializes a new instance of the [Graph](./) class. |
| [Graph](./graph/)(float, float) | Initializes a new instance of the [Graph](./) class. |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the border. |
| [set_GraphInfo](./set_graphinfo/)(System::SharedPtr\<Aspose::Pdf::GraphInfo\>) | Sets a [GraphInfo](../../aspose.pdf/graphinfo/) object that indicates the graph info,such as color, line width,etc. |
| [set_Height](./set_height/)(double) | Sets a float value that indicates the graph height. The unit is point. |
| virtual [set_HorizontalAlignment](../../aspose.pdf/baseparagraph/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsChangePosition](./set_ischangeposition/)(bool) | Sets change curret position after process paragraph.(default true) |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Left](./set_left/)(double) | Sets the table left coordinate. |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Shapes](./set_shapes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Shape\>\>\>) | Sets a [Shapes](../) collection that indicates all shapes in the graph. |
| [set_Title](./set_title/)(System::SharedPtr\<Aspose::Pdf::Text::TextFragment\>) | Sets a string value that indicates the title of the graph. |
| [set_Top](./set_top/)(double) | Sets the table top coordinate. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_Width](./set_width/)(double) | Sets a float value that indicates the graph width. The unit is point. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Drawing](../)
* Library [Aspose.PDF for C++](../../)
