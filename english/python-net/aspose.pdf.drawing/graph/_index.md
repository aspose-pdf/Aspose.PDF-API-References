---
title: Graph
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents graph - graphics generator paragraph.
type: docs
weight: 70
url: /python-net/aspose.pdf.drawing/graph/
---

## Graph class

Represents graph - graphics generator paragraph.

The Graph type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Graph(width, height)|Initializes a new instance of the Graph class|
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
|graph_info|Gets or sets a [graph_info](/pdf/python-net/aspose.pdf.drawing/graph/) object that indicates the graph info,such as color,<br/>            line width,etc.|
|border|Gets or sets the border.|
|is_change_position|Gets or sets change curret position after process paragraph.(default true)|
|left|Gets or sets the table left coordinate.|
|top|Gets or sets the table top coordinate.|
|shapes|Gets or sets a [shapes](/pdf/python-net/aspose.pdf.drawing/graph/) collection that indicates all shapes in the graph.|
|title|Gets or sets a string value that indicates the title of the graph.|
|width|Gets or sets a float value that indicates the graph width.<br/>            The unit is point.|
|height|Gets or sets a float value that indicates the graph height.<br/>            The unit is point.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clone the graph.|

### See Also

* namespace [aspose.pdf.drawing](/pdf/python-net/aspose.pdf.drawing/)
* assembly [Aspose.PDF](/pdf/python-net/)

