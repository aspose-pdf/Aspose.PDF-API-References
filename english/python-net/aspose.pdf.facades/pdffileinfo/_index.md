---
title: PdfFileInfo
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class for accessing meta information of PDF document.
type: docs
weight: 270
url: /python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Represents a class for accessing meta information of PDF document.

The PdfFileInfo type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileInfo()|Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class with default values.|
|PdfFileInfo(input_stream)|Initializes a new instance of the PdfFileInfo class|
|PdfFileInfo(input_stream, password)|Initializes a new instance of the PdfFileInfo class|
|PdfFileInfo(input_file)|Initializes a new instance of the PdfFileInfo class|
|PdfFileInfo(input_file, password)|Initializes a new instance of the PdfFileInfo class|
|PdfFileInfo(document)|Initializes a new instance of the PdfFileInfo class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|author|Gets or sets the Author information of PDF document.|
|is_encrypted|Checkes whether the PDF document is encrypted.|
|is_pdf_file|Checkes whether the source input is a valid PDF file.|
|use_strict_validation|Uses strict validation rules via using [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) property.|
|creation_date|Gets or sets the CreationDate information of PDF document.|
|creator|Gets or sets the Creator information of PDF document.|
|has_collection|Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it.|
|input_file|Gets or sets the input file.|
|input_stream|Gets or sets the input stream.|
|keywords|Gets or sets the Keywords information of PDF document.|
|mod_date|Gets or sets the ModDate date information of PDF document.|
|number_of_pages|Gets the number of document pages.|
|producer|Gets the Producer information of PDF document.|
|subject|Gets or sets the Subject information of PDF document.|
|title|Gets or sets the Title information of PDF document.|
|password_type|Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password.|
|has_open_password|Returns true if password is needed to open password protected pdf document.|
|has_edit_password|Returns true if password is needed to modify permissions or document security property.<br/>            Pay attention that this property can be read only if valid password was provided in [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) constructor.<br/>            In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/).|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_doc)|Initializes the facade.|
|bind_pdf(src_file)|Initializes the facade.|
|bind_pdf(src_stream)|Initializes the facade.|
|save(dest_stream)|Save updated PDF document into specified stream.|
|save(dest_file)|Save updated PDF document into specified file.|
|save_new_info(output_stream)|Save updated PDF document into specified stream.|
|save_new_info(output_file)|Save updated PDF document into specified file.|
|close()|Deinitializes the instance.|
|clear_info()|Clears all meta information of PDF document.|
|get_document_privilege()|Gets the PDF document privilege settings.|
|get_meta_info(name)|Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string.|
|get_page_height(page_num)|Gets the height of the specified page.|
|get_page_rotation(page_num)|Gets the rotation of the specified page.|
|get_page_width(page_num)|Gets the width of the specified page.|
|get_page_x_offset(page_num)|Gets the horizontal offset of the specified page display area.|
|get_page_y_offset(page_num)|Gets the vertical offset of the specified page display area.|
|get_pdf_version()|Gets the version info of PDF document.|
|set_meta_info(name, value)|Sets customized information of PDF document.|
|save_new_info_with_xmp(output_file_name)|Changes the properties specified explicitly by setting file information, other properties remain.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

