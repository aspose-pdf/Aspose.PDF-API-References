---
title: TeXFragment
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents TeX fragment.
type: docs
weight: 1510
url: /python-net/aspose.pdf/texfragment/
---

## TeXFragment class

Represents TeX fragment.

The TeXFragment type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TeXFragment(text)|Initializes a new instance of the TeXFragment class|
|TeXFragment(text, remove_indents)|Initializes a new instance of the TeXFragment class|
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
|te_x_load_options_of_instance|Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class.<br/>            Please use it when it's necessary use specific setting for import of LaTeX for this or that instance<br/>             (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources)<br/>            If parameter is default (null), then standard LaTeX loading options will be used.|
|latex_load_options_of_instance|Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class.<br/>            Please use it when it's necessary use specific setting for import of LaTeX for this or that instance<br/>             (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources)<br/>            If parameter is default (null), then standard LaTeX loading options will be used.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clones fragment.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

