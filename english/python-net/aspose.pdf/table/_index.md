---
title: Table
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a table that can be added to the page.
type: docs
weight: 1480
url: /python-net/aspose.pdf/table/
---

## Table class

Represents a table that can be added to the page.

The Table type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Table()|Initializes a new instance of the Table class|
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
|background_color|Gets or sets table background color|
|break_text|Gets or sets break text for table|
|corner_style|Gets or sets the styles of the border corners|
|repeating_rows_style|Gets the style for repeating rows|
|repeating_columns_count|Gets or sets the maximum columns count for table|
|repeating_rows_count|Gets the first rows count repeated for several pages|
|column_widths|Gets the column widths of the table.|
|broken|Gets or sets table vertial broken;|
|default_cell_border|Gets default cell border;|
|default_column_width|Gets default cell border;|
|rows|Gets the rows of the table.|
|border|Gets or sets the border.|
|default_cell_padding|Gets or sets the default cell padding.|
|default_cell_text_state|Gets or sets the default cell text state.|
|alignment|Gets or sets the table alignment.|
|left|Gets or sets the table left coordinate.|
|top|Gets or sets the table top coordinate.|
|is_broken|Gets or sets the table is broken - will be truncated for next page.|
|is_borders_included|Gets or sets border included in column widhts.|
|column_adjustment|Gets or sets the table column adjustment.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clone the table.|
|get_width()|Get width.|
|get_height(parent_page)|Get height.|
|set_column_text_state(col_number, text_state)|Set height.|
|import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled)|Imports one-dimensional array of data into table. Import goes one cell per each array's item and<br/>              starts from row and column defined in parameters. During import, if detected that necessary rows<br/>              are still absent(i.e. target table is too small to absorb all data), necessary rows will be created|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

