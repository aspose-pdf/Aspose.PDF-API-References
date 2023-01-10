---
title: HtmlFragment
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents html fragment.
type: docs
weight: 470
url: /python-net/aspose.pdf/htmlfragment/
---

## HtmlFragment class

Represents html fragment.

The HtmlFragment type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|HtmlFragment(text)|Initializes a new instance of the HtmlFragment class|
## Properties
| Name | Description |
| :- | :- |
|vertical_alignment|Gets or sets a vertical alignment of paragraph|
|horizontal_alignment|Gets or sets a horizontal alignment of paragraph|
|margin|Gets or sets a outer margin for paragraph (for pdf generation)|
|is_first_paragraph_in_column|Gets or sets a bool value that indicates whether this paragraph will be at next column.<br/>            Default is false.(for pdf generation)|
|is_kept_with_next|Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph.<br/>            Default is false.(for pdf generation)|
|is_in_new_page|Gets or sets a bool value that force this paragraph generates at new page.<br/>            Default is false.(for pdf generation)|
|is_in_line_paragraph|Gets or sets a paragraph is inline.<br/>            Default is false.(for pdf generation)|
|hyperlink|Gets or sets the fragment hyperlink(for pdf generator).|
|z_index|Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex <br/>            will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative <br/>            ZIndex will be placed behind the text in the page.|
|rectangle|Gets rectangle of the HtmlFragment|
|is_paragraph_has_margin|Gets or sets is paragraph has default margin otherwise margin is 0|
|is_break_words|Gets or sets words break|
|text_state|Gets or sets font|
|html_load_options|Gets or sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class.<br/>            Please use it when it's necessary use specific setting for import of HTML for this or that instance<br/>             (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources)<br/>            If parameter is default (null), then standard HTML loading options will be used.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clones html fragment.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

