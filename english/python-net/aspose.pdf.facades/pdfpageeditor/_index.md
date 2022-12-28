---
title: PdfPageEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.
type: docs
weight: 340
url: /python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.

The PdfPageEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfPageEditor()|Constructor for PdfPageEditor class.|
|PdfPageEditor(document)|Initializes a new instance of the PdfPageEditor class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|transition_duration|Gets or sets duration of the transition effect.|
|transition_type|Gets or sets transition style to use when moving to this page from another during a presentation.|
|display_duration|Gets or sets display duration for pages.|
|process_pages|Gets or sets the page numbers to be edited. By default, each page would be edited.|
|rotation|Gets or sets the rotation of the pages, the rotation must be 0, 90, 180 or 270.<br/>            Default value is 0.|
|zoom|Get or sets zoom coefficient. Value 1.0 corresponds to 100%.<br/>            Default value is 1.0.|
|page_size|Gets or sets the output file's page size.|
|alignment|Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.|
|horizontal_alignment|Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.|
|vertical_alignment|Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.|
|vertical_alignment_type|Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.|
|SPLITVOUT|Out Vertical Split|
|SPLITHOUT|Out Horizontal Split|
|SPLITVIN|In Vertical Split|
|SPLITHIN|IN Horizontal Split|
|BLINDV|Vertical Blinds|
|BLINDH|Vertical Blinds|
|INBOX|Inward Box|
|OUTBOX|Outward Box|
|LRWIPE|Left-Right Wipe|
|RLWIPE|Right-Left Wipe|
|BTWIPE|Bottom-Top Wipe|
|TBWIPE|Top-Bottom Wipe|
|DISSOLVE|The old page dissolves|
|LRGLITTER|Left-Right Glitter|
|TBGLITTER|Top-Bottom Glitter|
|DGLITTER|Diagonal Glitter|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(output_file)|Saves changed document into file.|
|save(output_stream)|Saves changed document into stream.|
|close()|Releases any resources associates with the current facade.|
|move_position(move_x, move_y)|Moves the origin from (0, 0) to the point that appointted. <br/>            The origin is left-bottom and the unit is point(1 inch = 72 points).|
|get_pages()|Returns total number of pages.|
|get_page_size(page)|Returns the page size of the specified page.|
|get_page_rotation(page)|Returns the rotation of specified page.|
|get_page_box_size(page, page_box_name)|Returns size of specified box in document.|
|apply_changes()|Apply changes made to the document pages.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

