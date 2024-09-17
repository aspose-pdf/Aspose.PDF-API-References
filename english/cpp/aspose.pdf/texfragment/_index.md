---
title: Aspose::Pdf::TeXFragment class
linktitle: TeXFragment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXFragment class. Represents TeX fragment in C++.'
type: docs
weight: 14900
url: /cpp/aspose.pdf/texfragment/
---
## TeXFragment class


Represents TeX fragment.

```cpp
class TeXFragment : public Aspose::Pdf::FormattedFragment
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../baseparagraph/baseparagraph/)() |  |
| [Clone](./clone/)() override | Clones fragment. |
| virtual [get_HorizontalAlignment](../baseparagraph/get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](../baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_LatexLoadOptionsOfInstance](./get_latexloadoptionsofinstance/)() const | Gets [TeXLoadOptions](../texloadoptions/) that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used. |
| [get_Margin](../baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_TeXLoadOptionsOfInstance](./get_texloadoptionsofinstance/)() const | Gets [TeXLoadOptions](../texloadoptions/) that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used. |
| virtual [get_VerticalAlignment](../baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_ZIndex](../baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| virtual [set_HorizontalAlignment](../baseparagraph/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](../baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_LatexLoadOptionsOfInstance](./set_latexloadoptionsofinstance/)(System::SharedPtr\<TeXLoadOptions\>) | Sets [TeXLoadOptions](../texloadoptions/) that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used. |
| [set_Margin](../baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_TeXLoadOptionsOfInstance](./set_texloadoptionsofinstance/)(System::SharedPtr\<TeXLoadOptions\>) | Sets [TeXLoadOptions](../texloadoptions/) that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used. |
| virtual [set_VerticalAlignment](../baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_ZIndex](../baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [TeXFragment](./texfragment/)(System::String) | Initializes a new instance of the [HtmlFragment](../htmlfragment/) class. |
| [TeXFragment](./texfragment/)(System::String, bool) | Initializes a new instance of the [HtmlFragment](../htmlfragment/) class. |
## See Also

* Class [FormattedFragment](../formattedfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
