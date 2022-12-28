---
title: PdfContentEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to edit PDF file's content.
type: docs
weight: 190
url: /python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Represents a class to edit PDF file's content.

The PdfContentEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfContentEditor()|The constructor of the PdfContentEditor object.|
|PdfContentEditor(document)|Initializes a new instance of the PdfContentEditor class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|text_search_options|Gets or sets text search options.|
|text_edit_options|Gets or sets text edit options.|
|text_replace_options|Gets or sets text replace options.|
|replace_text_strategy|A set of parameters for replace text operation|
|DOCUMENT_OPEN|A document event type. Opens a document.|
|DOCUMENT_CLOSE|A document event type. Closes a document.|
|DOCUMENT_WILL_SAVE|A document event type. Excute a action before saving.|
|DOCUMENT_SAVED|A document event type. Excute a action after saving.|
|DOCUMENT_WILL_PRINT|A document event type. Excute a action before printing.|
|DOCUMENT_PRINTED|A document event type. Excute a action after printing.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(input_file)|Binds a PDF file for editing.|
|bind_pdf(input_stream)|Binds a PDF stream for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves the PDF document to the specified file.|
|save(dest_stream)|Saves the PDF document to the specified stream.|
|create_web_link(rect, url, original_page, clr)|Creates a web link in PDF document.|
|create_web_link(rect, url, original_page)|Creates a web link in PDF document.|
|create_local_link(rect, des_page, original_page, clr)|Creates a local link in PDF document.|
|create_local_link(rect, des_page, original_page)|Creates a local link in PDF document.|
|create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr)|Creates a link to another PDF document page.|
|create_pdf_document_link(rect, remote_pdf, original_page, destination_page)|Creates a link to another PDF document page.|
|create_application_link(rect, application, page, clr)|Creates a link to launch an application in PDF document.|
|create_application_link(rect, application, page)|Creates a link to launch an application in PDF document.|
|create_file_attachment(rect, contents, file_path, page, name)|Creates file attachment annotation.|
|create_file_attachment(rect, contents, file_path, page, name, opacity)|Creates file attachment annotation.|
|create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name)|Creates file attachment annotation.|
|create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity)|Creates file attachment annotation.|
|add_document_attachment(file_attachment_path, description)|Adds document attachment with no annotation.|
|add_document_attachment(file_attachment_stream, file_attachment_name, description)|Adds document attachment with no annotation.|
|create_rubber_stamp(page, annot_rect, icon, annot_contents, color)|Creates a rubber stamp annotation.|
|create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file)|Creates a rubber stamp annotation.|
|create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream)|Creates a rubber stamp annotation.|
|delete_image(page_number, index)|Deletes the specified images on the specified page.|
|delete_image()|Deletes the specified images on the specified page.|
|replace_text(src_string, the_page, dest_string, text_state)|Replaces text in the PDF file on the specified page. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.|
|replace_text(src_string, dest_string)|Replaces text in the PDF file on the specified page. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.|
|replace_text(src_string, the_page, dest_string)|Replaces text in the PDF file on the specified page. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.|
|replace_text(src_string, dest_string, text_state)|Replaces text in the PDF file on the specified page. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.|
|replace_text(src_string, dest_string, font_size)|Replaces text in the PDF file on the specified page. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.|
|delete_stamp_by_ids(stamp_ids)|Deletes stamps with specified IDs from all pages of the document.|
|delete_stamp_by_ids(page_number, stamp_ids)|Deletes stamps with specified IDs from all pages of the document.|
|delete_stamp_by_id(page_number, stamp_id)|Deletes stamps with specified IDs from all pages of the document.|
|delete_stamp_by_id(stamp_id)|Deletes stamps with specified IDs from all pages of the document.|
|close()|Closes opened document.|
|extract_link()|Extracts the collection of Link instances contained in PDF document.|
|create_java_script_link(code, rect, original_page, color)|Creates a link to JavaScript in PDF document.|
|create_text(rect, title, contents, open, icon, page)|Creates text annotation in PDF document|
|create_free_text(rect, contents, page)|Creates free text annotation in PDF document|
|create_markup(rect, contents, type, page, clr)|Creates markup annotation it PDF document.|
|create_popup(rect, contents, open, page)|Creates popup annotation in PDF document.|
|delete_attachments()|Deletes all attachments in PDF document.|
|create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array)|Creates line annotation.|
|create_square_circle(rect, contents, clr, square, page, border_width)|Creates square-circle annotation.|
|draw_curve(line_info, page, annot_rect, annot_contents)|Creates curve annotation.|
|create_polygon(line_info, page, annot_rect, annot_contents)|Creates polygon annotation.|
|create_poly_line(line_info, page, annot_rect, annot_contents)|Creates polyline annotation.|
|create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color)|Creates caret annotation.|
|create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination)|Creates a bookmark with the specified action.|
|add_document_additional_action(event_type, code)|Adds additional action for document event.|
|remove_document_open_action()|Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup.|
|change_viewer_preference(viewer_attribution)|Changes the view preference.|
|get_viewer_preference()|Returns the view preference.|
|replace_image(page_number, index, image_file)|Replaces the specified image on the specified page of PDF document with another image.|
|create_movie(rect, file_path, page)|Creates Movie Annotations.|
|create_sound(rect, file_path, name, page, rate)|Creates Sound Annotations.|
|delete_stamp(page_number, index)|Deletes multiple stamps on the specified page by stamp indexes.|
|hide_stamp_by_id(page_number, stamp_id)|Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method.|
|show_stamp_by_id(page_number, stamp_id)|Shows stamp which was hidden by HiddenStampById.|
|move_stamp_by_id(page_number, stamp_id, x, y)|Changes position of the stamp on page.|
|move_stamp(page_number, stamp_index, x, y)|Changes position of the stamp on page.|
|get_stamps(page_number)|Returns array of stamps on the page.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

