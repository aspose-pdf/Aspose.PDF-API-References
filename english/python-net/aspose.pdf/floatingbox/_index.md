---
title: FloatingBox
second_title: Aspose.PDF for Python via .NET API Reference
description: 
type: docs
weight: 370
url: /python-net/aspose.pdf/floatingbox/
---

## FloatingBox class



The FloatingBox type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FloatingBox(width, height)|Initializes a new instance of the FloatingBox class|
|FloatingBox()|Initializes a new instance of the [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/) class.|
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
|column_info|Gets or sets a column info|
|width|Gets or sets a float value that indicates the width of the floating box.|
|height|Gets or sets a float value that indicates the height of the floating box.|
|is_need_repeating|Gets or sets a bool value that indicates whether the paragraph need to be repeated on next page.<br/>            Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.|
|paragraphs|Gets or sets a [paragraphs](/pdf/python-net/aspose.pdf/floatingbox/) collection that indicates all paragraphs in the cell.|
|border|Gets or sets a [BorderInfo](/pdf/python-net/aspose.pdf/borderinfo/) object that indicates the border info of the floating box.|
|background_color|Gets or sets a [Color](/pdf/python-net/aspose.pdf/color/) object that indicates the background color of the floating box.|
|background_image|Gets or sets background image for page (for generator only, not filled in when reading document).|
|padding|Gets or sets a [MarginInfo](/pdf/python-net/aspose.pdf/margininfo/) object that indicates the padding of the floating box.|
|left|Gets or sets the table left coordinate.|
|top|Gets or sets the table top coordinate.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clones a new [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/) object. Paragraphs in the floating box are not cloned.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

