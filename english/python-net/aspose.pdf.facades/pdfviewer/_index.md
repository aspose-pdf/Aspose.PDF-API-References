---
title: PdfViewer
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to view or print a pdf.
type: docs
weight: 370
url: /python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Represents a class to view or print a pdf.

The PdfViewer type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfViewer()|Initializes new [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) object.|
|PdfViewer(document)|Initializes a new instance of the PdfViewer class|
## Properties
| Name | Description |
| :- | :- |
|show_hidden_areas|Gets or sets flag that controls visibility of hidden areas on the page.|
|print_status|Gets the result of printing job. If success than null; otherwise, exception object.|
|use_intermidiate_image|Gets/sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important.|
|coordinate_type|Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.|
|print_as_image|Sets or gets a mode for PdfViewer to print as image.|
|page_count|Gets page count of the current Pdf file.|
|password|Gets or sets input document password.|
|print_page_dialog|Gets or sets a bool value that indicates whether produce the page number dialog when printing.|
|print_as_grayscale|Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false.|
|printer_job_name|Gets or sets name of document in printer queue when document is printed. Default value is file name.|
|form_presentation_mode|Gets or sets form presentation mode.|
|rendering_options|Gets or sets rendering options.|
|vertical_alignment|Gets or sets a value that indicates vertical alignment|
|horizontal_alignment|Gets or sets a value that indicates horizontal alignment|
|auto_resize|Gets or sets a bool value that indicates whether the file be printed with optimized size.|
|auto_rotate|Gets or sets a bool value that indicates whether the file be printed with auto rotation|
|auto_rotate_mode|Gets or sets a AutoRotateMode value that indicates direction of rotation|
|resolution|Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.|
|scale_factor|Gets or sets a floating point value that indicates scale factor. The default value is 1.0.|
## Methods
| Name | Description |
| :- | :- |
|print_large_pdf(file_path)|Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is <br/>             more than 3 MB, this method is recommended to get better performance.|
|print_large_pdf(input_stream)|Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is <br/>             more than 3 MB, this method is recommended to get better performance.|
|print_large_pdf(file_path, printer_settings)|Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds <br/>             of pages or more or its size is more than 3 MB, this method is recommended to get better performance.|
|print_large_pdf(input_stream, printer_settings)|Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds <br/>             of pages or more or its size is more than 3 MB, this method is recommended to get better performance.|
|print_large_pdf(file_path, page_settings, printer_settings)|Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf <br/>             file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to <br/>             get better performance.|
|print_large_pdf(input_stream, page_settings, printer_settings)|Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf <br/>             file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to <br/>             get better performance.|
|print_document_with_settings(page_settings, printer_settings)|Prints the Pdf document with settings. If the document size is not complatible to page size, pdf.kit will extend it to fit page size.|
|print_document_with_settings(printer_settings)|Prints the Pdf document with settings. If the document size is not complatible to page size, pdf.kit will extend it to fit page size.|
|open_pdf_file(file_path)|Opens a Pdf file, but does not actually decode the pages of the Pdf file.|
|open_pdf_file(input_stream)|Opens a Pdf file stream. But does not actually decode the pages of the Pdf file.|
|bind_pdf(src_file)|Initializes the facade.|
|bind_pdf(src_stream)|Initializes the facade.|
|bind_pdf(src_doc)|Initializes the facade.|
|save(dest_file)|Saves the result PDF document to file.|
|save(dest_stream)|Saves the result PDF document to stream.|
|decode_all_pages()|Get pages of current pdf file.|
|decode_page(page_number)|Decodes a page of one Pdf file.|
|print_document_with_setup()|Prints the Pdf document with a setup dialog. Choose a printer using the dialog.|
|print_document()|Prints the Pdf document with a setup dialog. Choose a printer using the dialog.|
|get_default_page_settings()|Gets the default page settings.|
|get_default_printer_settings()|Gets the default printer settings.|
|close_pdf_file()|Closes the current Pdf file.|
|close()|Closes the current Pdf file.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

