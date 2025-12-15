---
title: Aspose::Pdf::BaseParagraph class
linktitle: BaseParagraph
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BaseParagraph class. Represents a abstract base object can be added to the page(doc.Paragraphs.Add()) in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf/baseparagraph/
---
## BaseParagraph class


Represents a abstract base object can be added to the page(doc.Paragraphs.Add()).

```cpp
class BaseParagraph : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](./baseparagraph/)() |  |
| [Clone](./clone/)() override | Clones this instance. Virtual method. Always return null. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](./get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](./get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](./get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](./get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](./get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Margin](./get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| virtual [get_VerticalAlignment](./get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_ZIndex](./get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](./set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](./set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](./set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](./set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Margin](./set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| virtual [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_ZIndex](./set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
