---
title: PdfFileMend
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class for adding texts and images on the pages of existing PDF document.
type: docs
weight: 280
url: /python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Represents a class for adding texts and images on the pages of existing PDF document.

The PdfFileMend type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileMend()|Constructor.|
|PdfFileMend(input_file_name, output_file_name)|Initializes a new instance of the PdfFileMend class|
|PdfFileMend(input_stream, output_stream)|Initializes a new instance of the PdfFileMend class|
|PdfFileMend(document)|Initializes a new instance of the PdfFileMend class|
|PdfFileMend(document, output_file_name)|Initializes a new instance of the PdfFileMend class|
|PdfFileMend(document, dest_stream)|Initializes a new instance of the PdfFileMend class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|input_stream|Sets the input stream.|
|output_stream|Sets the output stream.|
|input_file|Sets the input file.|
|output_file|Sets the output file.|
|wrap_mode|Sets or gets word wrapping algorithm. See WordWrapMode and IsWordWrap.|
|text_positioning_mode|Sets or gets text positioning strategy. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Default mode is Legacy.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves the PDF document to the specified file.|
|save(dest_stream)|Saves the PDF document to the specified stream.|
|add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Adds image to the specified page of PDF document at specified coordinates.|
|add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters)|Adds image to the specified page of PDF document at specified coordinates.|
|add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Adds image to the specified pages of PDF document at specified coordinates.|
|add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters)|Adds image to the specified pages of PDF document at specified coordinates.|
|add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Adds image to the specified page of PDF document at specified coordinates.|
|add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters)|Adds image to the specified page of PDF document at specified coordinates.|
|add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Adds image to the specified pages of PDF document at specified coordinates.|
|add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters)|Adds image to the specified pages of PDF document at specified coordinates.|
|add_text(text, page_num, lower_left_x, lower_left_y)|Not implemented.|
|add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Not implemented.|
|add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y)|Not implemented.|
|close()|Closes PdfFileMend object.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

