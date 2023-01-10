---
title: PdfAnnotationEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class for work with PDF document annotations (comments).
type: docs
weight: 170
url: /python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Represents a class for work with PDF document annotations (comments).

The PdfAnnotationEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfAnnotationEditor()|Initializes new [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) object.|
|PdfAnnotationEditor(document)|Initializes a new instance of the PdfAnnotationEditor class|
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
|import_annotations_from_xfdf(xfdf_file)|Imports all annotations from XFDF file.|
|import_annotations_from_xfdf(xfdf_stream)|Imports all annotations from XFDF data stream.|
|import_annotation_from_xfdf(xfdf_file)|Imports all annotations from XFDF file.|
|import_annotation_from_xfdf(xfdf_file, annot_type)|Imports the specified annotations from XFDF file.|
|import_annotation_from_xfdf(xfdf_stream, annot_type)|Imports the specified annotations from XFDF data stream.|
|import_annotation_from_xfdf(xfdf_stream)|Imports the specified annotations from XFDF data stream.|
|import_annotations(annot_file, annot_type)|Imports the specified annotations into document from array of another PDF documents.|
|import_annotations(annot_file)|Imports the specified annotations into document from array of another PDF documents.|
|import_annotations(annot_file_stream, annot_type)|Imports the specified annotations into document from array of another PDF document streams.|
|import_annotations(annot_file_stream)|Imports the specified annotations into document from array of another PDF document streams.|
|flattening_annotations()|Flattens all annotations in the document.|
|flattening_annotations(flatten_settings)|Flattens all annotations in the document.|
|flattening_annotations(start, end, annot_type)|Flattens the annotations of the specified types.|
|delete_annotations()|Deletes all annotations in the document.|
|delete_annotations(annot_type)|Deletes all annotations of the specified type in the document.|
|export_annotations_xfdf(xml_output_stream, start, end, annot_types)|Exports the content of the specified annotation types into XFDF|
|export_annotations_xfdf(xml_output_stream, start, end, annot_types)|Exports the content of the specified annotations types into XFDF|
|extract_annotations(start, end, annot_types)|Gets the list of annotations of the specified types.|
|extract_annotations(start, end, annot_types)|Gets the list of annotations of the specified types.|
|close()|Releases any resources associates with the current facade.|
|modify_annotations_author(start, end, src_author, des_author)|Modifies the author of annotations on the specified page range.|
|delete_annotation(annot_name)|Deletes all annotations of the specified type in the document.|
|export_annotations_to_xfdf(xml_output_stream)|Exports annotations to stream.|
|modify_annotations(start, end, annotation)|Modifies the annotations of the specifed type on the specified page range.<br/>            It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open.|
|redact_area(page_index, rect, color)|Redacts area on the specified page. All contents is removed.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

