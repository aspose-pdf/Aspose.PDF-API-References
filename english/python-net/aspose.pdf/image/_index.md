---
title: Image
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents image.
type: docs
weight: 650
url: /python-net/aspose.pdf/image/
---

## Image class

Represents image.

The Image type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Image()|Initializes a new instance of the Image class|
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
|file|Gets or sets the image file.|
|fix_width|Gets or sets the image width.|
|fix_height|Gets or sets the image height.|
|file_type|Gets or sets the image file type.|
|image_scale|Gets or sets the image scale.|
|image_stream|Gets or sets the image stream.|
|is_apply_resolution|Gets or sets a bool value that indicates whether the image use resolution during generation|
|is_black_white|Gets or sets a bool value that indicates whether the image is forced to be black-and-white. If TIFF <br/>            image of CCITT subformat is used, this property must be set to true.|
|title|Gets or sets a string value that indicates the title of the image.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clone the image.|
|get_mime_type(i)|Returns mime type for image.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

