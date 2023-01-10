---
title: PdfBookmarkEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.
type: docs
weight: 180
url: /python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.

The PdfBookmarkEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfBookmarkEditor()|Initializes new [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) object.|
|PdfBookmarkEditor(document)|Initializes a new instance of the PdfBookmarkEditor class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves the PDF document to the specified file.|
|save(dest_stream)|Saves the PDF document to the specified stream.|
|create_bookmarks()|Creates bookmarks for all pages.|
|create_bookmarks(bookmark)|Creates bookmarks for all pages.|
|create_bookmarks(color, bold_flag, italic_flag)|Create bookmarks for all pages with specified color and style (bold, italic).|
|create_bookmark_of_page(bookmark_name, page_number)|Creates bookmark for the specified page.|
|create_bookmark_of_page(bookmark_name, page_number)|Creates bookmarks for the specified pages.|
|delete_bookmarks()|Deletes all bookmarks of the PDF document.|
|delete_bookmarks(title)|Deletes the bookmark of the PDF document.|
|extract_bookmarks()|Extracts bookmarks of all levels from the document.|
|extract_bookmarks(upper_level)|Extracts bookmarks of all levels from the document.|
|extract_bookmarks(title)|Extracts the bookmarks with the specified title.|
|extract_bookmarks(bookmark)|Extracts bookmarks of all levels from the document.|
|export_bookmarks_to_xml(xml_file)|Exports bookmarks to XML file.|
|export_bookmarks_to_xml(stream)|Exports bookmarks to XML stream.|
|import_bookmarks_with_xml(xml_file)|Imports bookmarks to the document from XML file.|
|import_bookmarks_with_xml(stream)|Imports bookmarks to the document from XML file.|
|close()|Releases any resources associates with the current facade.|
|modify_bookmarks(s_title, d_title)|Modifys bookmark title according to the specified bookmark title.|
|extract_bookmarks_to_html(pdf_file, css_file)|Exports bookmarks to HTML file.|
|export_bookmarks_to_html(in_pdf_file, out_html_file)|Exports bookmarks to HTML file.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

