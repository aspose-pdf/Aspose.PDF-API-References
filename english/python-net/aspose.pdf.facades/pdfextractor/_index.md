---
title: PdfExtractor
second_title: Aspose.PDF for Python via .NET API Reference
description: Class for extracting images and text from PDF document.
type: docs
weight: 210
url: /python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Class for extracting images and text from PDF document.

The PdfExtractor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfExtractor()|Initializes new [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) object.|
|PdfExtractor(document)|Initializes a new instance of the PdfExtractor class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|start_page|Gets or sets start page in the page range where extracting operation will be performed.|
|end_page|Gets or sets end page in the page range where extracting operation will be performed.|
|extract_text_mode|Sets the mode for extract text's result.|
|text_search_options|Gets or sets text search options.|
|extract_image_mode|Sets the mode for extract images process.|
|is_bidi|Is true when text has hebriew or arabic symbols. This case must be specially considered because<br/>            string functions change their behaviour and start process text from right to left (except numbers <br/>            and other non text chars).|
|resolution|Set or gets resolution for extracted images.<br/>            Default value is 150.<br/>            Images which have greater resolution value are more clear.<br/>            However increasing resolution value results in increasing time and memory needed to extract images.<br/>            Usually to get clear image it's enough to set resolution to 150 or 300.|
|password|Gets or sets input file's password.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(input_file)|Bind input PDF file.|
|bind_pdf(input_stream)|Binds PDF document from stream.|
|bind_pdf(src_doc)|Initializes the facade.|
|extract_text()|Extracts text from a Pdf document using Unicode encoding.|
|extract_text(encoding)|Extracts text from a Pdf document using specified encoding.|
|get_text(output_file)|Saves text to file. see also:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/)|
|get_text(output_stream)|Saves text to stream. see also:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/)|
|get_text(output_stream, filter_not_ascii)|Saves text to stream. see also:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/)|
|get_next_image(output_file)|Retreives next image from PDF document. Note: ExtractImage must be called before using of this method.|
|get_next_image(output_file, format)|Retreives next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.|
|get_next_image(output_stream, format)|Retreive next image from PDF file and stores it into stream with given image format.|
|get_next_image(output_stream)|Retreive next image from PDF file and stores it into stream with given image format.|
|extract_attachment()|Extracts attachments from a Pdf document.|
|extract_attachment(attachment_file_name)|Extracts attachment to PDF file by attachment name.|
|get_next_page_text(output_file)|Saves one page's text to file.|
|get_next_page_text(output_stream)|Saves one page's text to stream.|
|close()|Disposes Aspose.Pdf.Document bound with a facade.|
|extract_image()|Extract images from PDF file.|
|has_next_image()|Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method.|
|get_attach_names()|Returns list of attachments in PDF file. Note: ExtractAttachments must be called befor using this method.|
|get_attachment(output_path)|Stores attachment into file.|
|has_next_page_text()|Indicates that whether can get more texts or not.|
|get_attachment_info()|Gets the list of attachments.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

