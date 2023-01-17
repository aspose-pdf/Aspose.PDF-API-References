---
title: PdfFileEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Implements operations with PDF file concatenation, splitting, extracting pages, making booklet, etc.
type: docs
weight: 220
url: /python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.

The PdfFileEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileEditor()|Initializes a new instance of the PdfFileEditor class|
## Properties
| Name | Description |
| :- | :- |
|conversion_log|Gets log of conversion process.|
|merge_duplicate_layers|Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. <br/>            Else, layers with equal names will be save as different layers in resultant document.|
|copy_outlines|If true then outlines will be copied.|
|copy_logical_structure|If true then logical structure of the file is copied when concatenation is performed.|
|merge_duplicate_outlines|If true, duplicate outlines are merged.|
|preserve_user_rights|If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.|
|incremental_updates|If true, incremental updates are made during concatenation.|
|optimize_size|Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. <br/>            This allows to decrease resultant file size but may cause slower execution and larger memory requirements.<br/>            Default value: false.|
|corrupted_items|Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate() <br/>            function new CorruptedItem entry is created.<br/>            This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted.|
|corrupted_file_action|This property defines behavior when concatenating process met corrupted file.<br/>            Possible values are: StopWithError and ConcatenateIgnoringCorrupted.|
|owner_password|Sets owner's password if the source input Pdf file is encrypted.<br/>            This property is not implemented yet.|
|allow_concatenate_exceptions|If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.|
|close_concatenated_streams|If set to true, streams are closed after operation.|
|unique_suffix|Format of the suffix which is added to field name to make it unique when forms are concatenated.<br/>            This string must contain %NUM% substring which will be replaced with numbers.<br/>            For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.|
|keep_actions|If true actions will be copied from source documents. Defaulkt value : true.|
|keep_fields_unique|If true then field names will be made unique when forms are concatenated.<br/>            Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.|
|remove_signatures|If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.|
|use_disk_buffer|If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.|
|concatenation_packet_size|Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.|
## Methods
| Name | Description |
| :- | :- |
|try_concatenate(first_input_file, sec_input_file, output_file)|Concatenates two files.|
|try_concatenate(src, dest)|Concatenates documents.|
|try_concatenate(input_files, output_file)|Concatenates files into one file.|
|try_concatenate(input_stream, output_stream)|Concatenates files|
|try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file)|Concatenates two files.|
|try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream)|Concatenates files|
|try_append(input_stream, port_streams, start_page, end_page, output_stream)|Appends pages, which are chosen from array of documents in portStreams.<br/>            The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.|
|try_append(input_file, port_files, start_page, end_page, output_file)|Appends pages, which are chosen from portFiles documents. <br/>            The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.|
|try_insert(input_file, insert_location, port_file, page_number, output_file)|Inserts pages from an other file into the input Pdf file.|
|try_insert(input_stream, insert_location, port_stream, page_number, output_stream)|Inserts pages from an other file into the input Pdf file.|
|try_delete(input_file, page_number, output_file)|Deletes pages specified by number array from input file, saves as a new Pdf file.|
|try_delete(input_stream, page_number, output_stream)|Deletes pages specified by number array from input file, saves as a new Pdf file.|
|try_extract(input_file, start_page, end_page, output_file)|Extracts pages from input file,saves as a new Pdf file.|
|try_extract(input_file, page_number, output_file)|Extracts pages specified by number array, saves as a new PDF file.|
|try_extract(input_stream, page_number, output_stream)|Extracts pages specified by number array, saves as a new Pdf file.|
|try_split_from_first(input_file, location, output_file)|Splits Pdf file from first page to specified location,and saves the front part as a new file.|
|try_split_from_first(input_stream, location, output_stream)|Splits from start to specified location,and saves the front part in output Stream.|
|try_split_to_end(input_file, location, output_file)|Splits from location, and saves the rear part as a new file.|
|try_split_to_end(input_stream, location, output_stream)|Splits from specified location, and saves the rear part as a new file Stream.|
|try_make_booklet(input_file, output_file)|Makes booklet from the input file to output file.|
|try_make_booklet(input_stream, output_stream)|Makes booklet from the InputStream to outputStream.|
|try_make_booklet(input_file, output_file, page_size)|Makes booklet from the inputFile to outputFile.|
|try_make_booklet(input_stream, output_stream, page_size)|Makes booklet from the input stream and save result into output stream.|
|try_make_booklet(input_file, output_file, left_pages, right_pages)|Makes customized booklet from the firstInputFile to outputFile.|
|try_make_booklet(input_stream, output_stream, left_pages, right_pages)|Makes customized booklet from the firstInputStream to outputStream.|
|try_make_booklet(input_file, output_file, page_size, left_pages, right_pages)|Makes customized booklet from the firstInputFile to outputFile.|
|try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages)|Makes booklet from the firstInputStream to outputStream.|
|try_make_n_up(input_file, output_file, x, y)|Makes N-Up document from the firstInputFile to outputFile.|
|try_make_n_up(input_stream, output_stream, x, y)|Makes N-Up document from the input stream and saves result into output stream.|
|try_make_n_up(input_stream, output_stream, x, y, page_size)|Makes N-Up document from the first input stream to output stream.|
|try_make_n_up(first_input_file, second_input_file, output_file)|Makes N-Up document from the firstInputFile to outputFile.|
|try_make_n_up(first_input_stream, second_input_stream, output_stream)|Makes N-Up document from the input stream and saves result into output stream.|
|try_make_n_up(input_files, output_file, is_sidewise)|Makes N-Up document from the multi input PDF files to outputFile. <br/>            Each page of outputFile will contain multi pages, which are combination with pages <br/>            in the input files of the same page number. The multi pages piled up horizontally <br/>            if isSidewise is true and piled up vertically if isSidewise is false.|
|try_make_n_up(input_streams, output_stream, is_sidewise)|Makes N-Up document from the multi input PDF streams to outputStream.<br/>            Each page of outputStream will contain multi pages, which are combination with pages <br/>            in the input streams of the same page number. The multi-pages piled up horizontally <br/>            if isSidewise is true and piled up vertically if isSidewise is false.|
|try_make_n_up(input_file, output_file, x, y, page_size)|Makes N-Up document from the input file to outputFile.|
|try_resize_contents(source, destination, pages, parameters)|Resizes contents of pages of the document.|
|try_resize_contents(source, destination, pages, new_width, new_height)|Resizes contents of document pages. <br/>            Shrinks contents of page and adds margins.<br/>            New size of contents is specified in default space units.|
|try_resize_contents(source, destination, pages, parameters)|Resizes contents of pages in document. If page is shrinked blank margins are added around the page.|
|concatenate(first_input_file, sec_input_file, output_file)|Concatenates files and saves reslt into HttpResposnse object.|
|concatenate(first_input_stream, sec_input_stream, output_stream)|Concatenates files and stores result into HttpResponse object.|
|concatenate(src, dest)|Concatenates documents.|
|concatenate(input_files, output_file)|Concatenates files and saves reslt into HttpResposnse object.|
|concatenate(input_stream, output_stream)|Concatenates files and stores result into HttpResponse object.|
|concatenate(first_input_file, sec_input_file, blank_page_file, output_file)|Concatenates files and saves reslt into HttpResposnse object.|
|concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream)|Concatenates files and stores result into HttpResponse object.|
|append(input_stream, port_streams, start_page, end_page, output_stream)|Appends documents to source document and saves result into response object.|
|append(input_file, port_files, start_page, end_page, output_file)|Appends documents to source document and saves result into HttpResponse object.|
|append(input_file, port_file, start_page, end_page, output_file)|Appends documents to source document and saves result into HttpResponse object.|
|append(input_stream, port_stream, start_page, end_page, output_stream)|Appends documents to source document and saves result into response object.|
|insert(input_file, insert_location, port_file, start_page, end_page, output_file)|Inserts contents of file into source file and stores result into HttpResponse object.|
|insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream)|Inserts document into other document and stores result into response object.|
|insert(input_file, insert_location, port_file, page_number, output_file)|Inserts contents of file into source file and stores result into HttpResponse object.|
|insert(input_stream, insert_location, port_stream, page_number, output_stream)|Inserts document into other document and stores result into response object.|
|delete(input_file, page_number, output_file)|Deletes specified pages from document and stores result into HttpResponse object.|
|delete(input_stream, page_number, output_stream)|Deletes specified pages from document and saves result into HttpResponse object.|
|extract(input_file, start_page, end_page, output_file)|Extracts specified pages from source file and stores result into HttpResponse object.|
|extract(input_file, page_number, output_file)|Extracts specified pages from source file and stores result into HttpResponse object.|
|extract(input_stream, start_page, end_page, output_stream)|Extracts specified pages form source file and stores result into  HttpResponse object.|
|extract(input_stream, page_number, output_stream)|Extracts specified pages form source file and stores result into  HttpResponse object.|
|split_from_first(input_file, location, output_file)|Splits document from first page to location and saves result into HttpResponse objects.|
|split_from_first(input_stream, location, output_stream)|Splits document from start to specified location and stores result into HttpResponse object.|
|split_to_end(input_file, location, output_file)|Splits from specified location, and saves the rear part into HttpResponse object.|
|split_to_end(input_stream, location, output_stream)|Splits from specified location, and saves the rear part into HttpResponse object.|
|make_booklet(input_file, output_file)|Makes booklet from source file and stores result into HttpResponse objects.|
|make_booklet(input_stream, output_stream)|Make booklet from PDF file and stores it into HttpResponse.|
|make_booklet(input_file, output_file, page_size)|Makes booklet from source file and stores result into HttpResponse objects.|
|make_booklet(input_stream, output_stream, page_size)|Make booklet from PDF file and stores it into HttpResponse.|
|make_booklet(input_file, output_file, left_pages, right_pages)|Makes booklet from source file and stores result into HttpResponse objects.|
|make_booklet(input_stream, output_stream, left_pages, right_pages)|Make booklet from PDF file and stores it into HttpResponse.|
|make_booklet(input_file, output_file, page_size, left_pages, right_pages)|Makes booklet from source file and stores result into HttpResponse objects.|
|make_booklet(input_stream, output_stream, page_size, left_pages, right_pages)|Make booklet from PDF file and stores it into HttpResponse.|
|make_n_up(input_file, output_file, x, y)|Makes N-up document and stores result into HttpResponse object.|
|make_n_up(input_stream, output_stream, x, y)|Makes N-up document and stores result into HttpResponse object.|
|make_n_up(input_stream, output_stream, x, y, page_size)|Makes N-up document and stores result into HttpResponse object.|
|make_n_up(first_input_file, second_input_file, output_file)|Makes N-up document and stores result into HttpResponse object.|
|make_n_up(first_input_stream, second_input_stream, output_stream)|Makes N-up document and stores result into HttpResponse object.|
|make_n_up(input_files, output_file, is_sidewise)|Makes N-Up document from the multi input PDF files to outputFile. <br/>            Each page of outputFile will contain multi pages, which are combination with pages <br/>            in the input files of the same page number. The multi pages piled up horizontally <br/>            if isSidewise is true and piled up vertically if isSidewise is false.|
|make_n_up(input_streams, output_stream, is_sidewise)|Makes N-Up document from the multi input PDF streams to outputStream.<br/>            Each page of outputStream will contain multi pages, which are combination with pages <br/>            in the input streams of the same page number. The multi-pages piled up horizontally <br/>            if isSidewise is true and piled up vertically if isSidewise is false.|
|make_n_up(input_file, output_file, x, y, page_size)|Makes N-up document and stores result into HttpResponse object.|
|split_to_pages(input_file, file_name_template)|Splits the PDF file into single-page documents.|
|split_to_pages(input_stream, file_name_template)|Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.|
|resize_contents(source, destination, pages, parameters)|Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.|
|resize_contents(source, destination, pages, new_width, new_height)|Resizes contents of document pages. <br/>            Shrinks contents of page and adds margins.<br/>            New size of contents is specified in default space units.|
|resize_contents(source, destination, pages, new_width, new_height)|Resizes contents of document pages. <br/>            Shrinks contents of page and adds margins.<br/>            New size of contents is specified in default space units.|
|resize_contents(source, destination, pages, parameters)|Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.|
|resize_contents(source, pages, parameters)|Resizes pages of document. Blank margins are added around of shrinked page.|
|resize_contents(source, parameters)|Resizes pages of document. Blank margins are added around of shrinked page.|
|resize_contents_pct(source, destination, pages, new_width, new_height)|Resizes contents of document pages.<br/>            Shrinks contents of page and adds margins.<br/>            New contents size is specified in percents.|
|resize_contents_pct(source, destination, pages, new_width, new_height)|Resizes contents of document pages.<br/>            Shrinks contents of page and adds margins.<br/>            New contents size is specified in percents.|
|add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin)|Resizes page contents and add specifed margins. <br/>            Margins are specified in default space units.|
|add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin)|Resizes page contents and add specifed margins. <br/>            Margins are specified in default space units.|
|add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin)|Resizes page contents and add specified margins.<br/>            Margins are specified in percents of intitial page size.|
|add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin)|Resizes page contents and add specified margins.<br/>            Margins are specified in percents of intitial page size.|
|add_page_break(src, dest, page_breaks)|Adds page breaks into document pages.|
|add_page_break(src, dest, page_breaks)|Adds page breaks into document pages.|
|add_page_break(src, dest, page_breaks)|Adds page breaks into document pages.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

