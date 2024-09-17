---
title: Aspose::Pdf::FormattedFragment class
linktitle: FormattedFragment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FormattedFragment class. Represents abstract formatted fragment in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf/formattedfragment/
---
## FormattedFragment class


Represents abstract formatted fragment.

```cpp
class FormattedFragment : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../baseparagraph/baseparagraph/)() |  |
| [Clone](../baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| virtual [get_HorizontalAlignment](../baseparagraph/get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](../baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Margin](../baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| virtual [get_VerticalAlignment](../baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_ZIndex](../baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| virtual [set_HorizontalAlignment](../baseparagraph/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](../baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Margin](../baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| virtual [set_VerticalAlignment](../baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_ZIndex](../baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
