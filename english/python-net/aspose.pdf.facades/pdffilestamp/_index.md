---
title: PdfFileStamp
second_title: Aspose.PDF for Python via .NET API Reference
description: Class for adding stamps (watermark or background) to PDF files.
type: docs
weight: 320
url: /python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Class for adding stamps (watermark or background) to PDF files.

The PdfFileStamp type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileStamp(input_file, output_file)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp(input_stream, output_stream)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp(input_file, output_file, keep_security)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp(input_stream, output_stream, keep_security)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp()|Constructor of the PdfFileStamp.<br/>            Input file and output file may be specified via corresponding properties.|
|PdfFileStamp(document)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp(document, output_file)|Initializes a new instance of the PdfFileStamp class|
|PdfFileStamp(document, output_stream)|Initializes a new instance of the PdfFileStamp class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|optimize_size|Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. <br/>            This allows to decrease resultant file size but may cause slower execution and larger memory requirements.<br/>            Default value: false.|
|keep_security|Keeps security if true. (This feature will be implemented in next versions).|
|input_file|Gets or sets name and path of input file.|
|input_stream|Gets or sets input stream.|
|output_file|Gets or sets name and path of output file.|
|output_stream|Gets or sets output stream.|
|page_number_rotation|Gets or sets rotation of page number. Rotation  is in degrees. Default is 0.|
|page_height|Gets height of first page in souorce file.|
|page_width|Gets width of first page in input file.|
|starting_number|Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. <br/>            For example if  StartingNumber is set to 100, document pages will have numbers 100, 101, 102...|
|numbering_style|Gets or sets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase|
|stamp_id|Stamp ID of next added stamp (incluiding page headers/hooters/page numbers).|
|POS_BOTTOM_MIDDLE|Bottom middle position.|
|POS_BOTTOM_RIGHT|Bottom right position.|
|POS_UPPER_RIGHT|Right upper position.|
|POS_SIDES_RIGHT|Right position.|
|POS_UPPER_MIDDLE|Upper middle position.|
|POS_BOTTOM_LEFT|Bottom left position.|
|POS_SIDES_LEFT|Left position.|
|POS_UPPER_LEFT|Upper let position.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves result into specified file.|
|save(dest_stream)|Saves document into specified stream.|
|add_page_number(format_string)|Add page number to file. Page number text may contain # sign which will be replaced with number of the page. <br/>            Page number is placed in the bottom of the page centered horizontally.|
|add_page_number(formatted_text)|Adds page number to the page. Page number may contain # sign which will be replaced with page number.<br/>            Page number is placed in the bottom of the page centered horizontally.|
|add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin)|Adds page number to the pages of document.|
|add_page_number(format_string, x, y)|Adds page number to the pages of document.|
|add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin)|Adds page number to the pages of document.|
|add_page_number(formatted_text, x, y)|Adds page number to the pages of document.|
|add_page_number(format_string, position)|Adds page number to the pages of document.|
|add_page_number(formatted_text, position)|Adds page number to the pages of document.|
|add_header(formatted_text, top_margin)|Adds header to the page.|
|add_header(formatted_text, top_margin, left_margin, right_margin)|Adds header to the page.|
|add_header(image_file, top_margin)|Adds image as header to the pages of the file.|
|add_header(image_file, top_margin, left_margin, right_margin)|Adds image as header to the pages of the file.|
|add_header(image_stream, top_margin)|Adds image as header on the pages.|
|add_header(input_stream, top_margin, left_margin, right_margin)|Adds image as header on the pages.|
|add_footer(formatted_text, bottom_margin)|Adds footer to the pages of the document.|
|add_footer(formatted_text, bottom_margin, left_margin, right_margin)|Adds footer to the pages of the document.|
|add_footer(image_file, bottom_margin)|Adds image as footer to the pages of the document.|
|add_footer(image_file, bottom_margin, left_margin, right_margin)|Adds image as footer to the pages of the document.|
|add_footer(image_stream, bottom_margin)|Adds image as footer of the page.|
|add_footer(image_stream, bottom_margin, left_margin, right_margin)|Adds image as footer of the page.|
|close()|Closes opened files and saves changes. <br/>            Warning. If input or output streams are specified they are not closed by Close() method.|
|add_stamp(stamp)|Adds stamp to the file.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

