---
title: Document
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing PDF document
type: docs
weight: 230
url: /python-net/aspose.pdf/document/
---

## Document class

Class representing PDF document

The Document type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Document(input)|Initializes a new instance of the Document class|
|Document(input, password, is_managed_stream)|Initializes a new instance of the Document class|
|Document(input, is_managed_stream)|Initializes a new instance of the Document class|
|Document(filename)|Initializes a new instance of the Document class|
|Document(input, password)|Initializes a new instance of the Document class|
|Document()|Initializes empty document.|
|Document(filename, options)|Initializes a new instance of the Document class|
|Document(input, options)|Initializes a new instance of the Document class|
|Document(filename, password)|Initializes a new instance of the Document class|
|Document(filename, password, is_managed_stream)|Initializes a new instance of the Document class|
## Properties
| Name | Description |
| :- | :- |
|java_script|Collection of JavaScript of document level.|
|is_licensed|Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise.|
|page_info|Gets or sets the page info.(for generator only, not filled in when reading document)|
|enable_signature_sanitization|Gets or sets flag to manage signature fields sanitization. Enabled by default.|
|is_pdfa_compliant|Gets the is document pdfa compliant.|
|is_pdf_ua_compliant|Gets the is document pdfua compliant.|
|is_xref_gaps_allowed|Gets or sets  the is document pdfa compliant.|
|named_destinations|Collection of Named Destination in the document.|
|destinations|Gets the collection of destinations.<br/>            Obsolete. Please use NamedDestinations.|
|pdf_format|Gets PDF format|
|embed_standard_fonts|Property which declares that document must embed all standard Type1 fonts <br/>            which  has flag IsEmbedded set into true. All PDF fonts can be embedded <br/>            into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule.<br/>            Standard Type1 font embedding requires much time, so to embed these fonts it's necessary<br/>            not only set flag IsEmbedded into true for specified font but also set <br/>            an additiona flag on document's level - EmbedStandardFonts = true;<br/>            This property can be set only one time for all fonts.<br/>            By default false.|
|disable_font_license_verifications|Many operations with font can't be executed if these operations are prohibited by license of this font. <br/>            For example some font can't be embedded into PDF document if license rules disable embedding for this font. <br/>            This flag is used to disable any license restrictions for all fonts in current PDF document.<br/>            Be careful when using this flag. When it is set it means that person who sets this flag, <br/>            takes all responsibility of possible license/law violations on himself. <br/>            So He takes it on it's own risk. <br/>            It's strongly recommended to use this flag only when you are fully confident that you are not breaking <br/>            the copyright law. <br/>            By default false.|
|font_utilities|IDocumentFontUtilities instance|
|collection|Gets collection of document.|
|version|Gets a version of Pdf from Pdf file header.|
|open_action|Gets or sets action performed at document opening.|
|hide_tool_bar|Gets or sets flag specifying whether toolbar should be hidden when document is active.|
|hide_menubar|Gets or sets flag specifying whether menu bar should be hidden when document is active.|
|hide_window_ui|Gets or sets flag specifying whether user interface elements should be hidden when document is active.|
|fit_window|Gets or sets flag specifying whether document window must be resized to fit the first displayed page.|
|center_window|Gets or sets flag specifying whether position of the document's window will be centerd on the screen.|
|display_doc_title|Gets or sets flag specifying whether document's window title bar should display document title.|
|pages|Gets or sets collection of document pages.<br/>            Note that pages are numbered from 1 in collection.|
|outlines|Gets document outlines.|
|actions|Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions.|
|form|Gets Acro Form of the document.|
|embedded_files|Gets collection of files embedded to document.|
|direction|Gets or sets reading order of text: L2R (left to right) or R2L (right to left).|
|page_mode|Gets or sets page mode, specifying how document should be displayed when opened.|
|non_full_screen_page_mode|Gets or sets page mode, specifying how to display the document on exiting full-screen mode.|
|page_layout|Gets or sets page layout which shall be used when the document is opened.|
|duplex|Gets or sets print duplex mode handling option to use when printing the file from the print dialog.|
|file_name|Name of the PDF file that caused this document|
|info|Gets document info.|
|metadata|Document metadata.<br/>            (A PDF document may include general information,<br/>             such as the document's title, author, and creation and modification dates.<br/>             Such global information about the document (as opposed to its content or structure) is called metadata<br/>             and is intended to assist in cataloguing and searching for documents in external databases.)|
|logical_structure|Gets logical structure of the document.|
|handle_signature_change|Throw Exception if the document will save with changes and have signature|
|crypto_algorithm|Gets security settings if document is encrypted. <br/>            If document is not encrypted then corresponding exception will be raised in .net 1.1<br/>            or CryptoAlgorithm will be null for other .net versions.|
|is_linearized|Gets or sets a value indicating whether document is linearized.|
|permissions|Gets permissions of the document.|
|is_encrypted|Gets encrypted status of the document. True if document is encrypted.|
|id|Gets the ID.|
|background|Gets or sets the background color of the document.|
|optimize_size|Gets or sets optimization flag. When pages are added to document, equal resource streams in resultant file are<br/>            merged into one PDF object if this flag set. <br/>            This allows to decrease resultant file size but may cause slower execution and larger memory requirements.<br/>            Default value: false.|
|allow_reuse_page_content|Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the <br/>            same content object. Please note that this mode may cause side effects like changing page content when other page is changed.|
|ignore_corrupted_objects|Gets or sets flag of ignoring errors in source files. <br/>            When pages from source document copied into destination document, copying process is stopped with exception <br/>            if some objects in source files are corrupted when this flag is false. <br/>            example: dest.Pages.Add(src.Pages);<br/>            If this flag is set to true then corrupted objects will be replaced with empty values.<br/>            By default: true.|
|page_labels|Gets page labels in the document.|
|enable_object_unload|Get or sets flag which enables document partially be unloaded from memory. <br/>            This allow to decrease memory usage but may have negative effect on perfomance.|
|tagged_content|Gets access to TaggedPdf content.|
## Methods
| Name | Description |
| :- | :- |
|save(output)|Stores document into stream.|
|save(output_file_name)|Saves document into the specified file.|
|save()|Stores document into stream.|
|save(options)|Saves the document with save options.|
|save(output_file_name, format)|Saves the document with a new name along with a file format.|
|save(output_stream, format)|Saves the document with a new name along with a file format.|
|save(output_file_name, options)|Saves the document with a new name setting its save options.|
|save(output_stream, options)|Saves the document to a stream with a save options.|
|export_annotations_to_xfdf(file_name)|Exports all document annotations to XFDF file|
|export_annotations_to_xfdf(stream)|Export all document annotations into stream.|
|send_to(device, output)|Sends the whole document to the document device for processing.|
|send_to(device, from_page, to_page, output)|Sends the certain pages of the document to the document device for processing.|
|send_to(device, output_file_name)|Sends the whole document to the document device for processing.|
|send_to(device, from_page, to_page, output_file_name)|Sends the whole document to the document device for processing.|
|import_annotations_from_xfdf(file_name)|Imports annotations from XFDF file to document.|
|import_annotations_from_xfdf(stream)|Imports annotations from stream to document.|
|validate(output_log_file_name, format)|Validate document into the specified file.|
|validate(output_log_stream, format)|Validate document into the specified file.|
|validate(options)|Validate document into the specified file.|
|convert(output_log_file_name, format, action, transparency_action)|Convert document and save errors into the specified file.|
|convert(output_log_stream, format, action, transparency_action)|Convert document and save errors into the specified file.|
|convert(output_log_file_name, format, action)|Convert document and save errors into the specified file.|
|convert(options)|Convert document using specified conversion options|
|convert(output_log_stream, format, action)|Convert document and save errors into the specified file.|
|convert(fixup, output_log, only_validation, parameters)|Convert document by applying the Fixup.|
|convert(fixup, output_log, only_validation, parameters)|Convert document by applying the Fixup.|
|convert(src_file_name, load_options, dst_file_name, save_options)|Converts source file in source format into destination file in destination format.|
|convert(src_stream, load_options, dst_file_name, save_options)|Converts stream in source format into destination file in destination format.|
|convert(src_file_name, load_options, dst_stream, save_options)|Converts stream in source format into destination file in destination format.|
|convert(src_stream, load_options, dst_stream, save_options)|Converts stream in source format into destination file in destination format.|
|flatten()|Removes all fields from the document and place their values instead.|
|flatten(flatten_settings)|Removes all fields from the document and place their values instead.|
|encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20)|Encrypts the document. Call then Save to get encrypted version of the document.|
|encrypt(user_password, owner_password, permissions, crypto_algorithm)|Encrypts the document. Call then Save to get encrypted version of the document.|
|encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20)|Encrypts the document. Call then Save to get encrypted version of the document.|
|optimize_resources()|Optimize resources in the document:<br/>            1. Resources which are not used on the document pages are removed;<br/>            2. Equal resources are joined into one object; <br/>            3. Unused objects are deleted.|
|optimize_resources(strategy)|Optimize resources in the document according to defined optimization strategy.|
|bind_xml(file)|Bind xml to document|
|bind_xml(xml_file, xsl_file)|Bind xml to document|
|bind_xml(xml_stream, xsl_stream)|Bind xml/xsl to document|
|bind_xml(stream)|Bind xml/xsl to document|
|remove_pdfa_compliance()|Remove pdfa compliance from the document|
|remove_pdf_ua_compliance()|Remove pdfUa compliance from the document|
|set_title(title)|Set Title for Pdf Document|
|process_paragraphs()|Process paragraphs for generator.|
|remove_metadata()|Removes metadata from the document.|
|change_passwords(owner_password, new_user_password, new_owner_password)|Changes document passwords. This action can be done only using owner password.|
|decrypt()|Decrypts the document. Call then Save to obtain decrypted version of the document.|
|optimize()|Linearize document in order to<br/>            - open the first page as quickly as possible;<br/>            - display next page or follow by link to the next page as quickly as possible;<br/>            - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first);<br/>            - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed.<br/>            Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure,<br/>            call then Save to get optimized document.|
|get_catalog_value(key)|Returns item value from catalog dictionary.|
|free_memory()|Clears memory|
|save_xml(file)|Save document to XML.|
|get_object_by_id(id)|Gets a object with specified ID in the document.|
|repair()|Repairs broken document.|
|get_xmp_metadata(stream)|Get XMP metadata from document.|
|set_xmp_metadata(stream)|Set XMP metadata of document.|
|check(do_repair)|Validates document.|
|page_nodes_to_balanced_tree(nodes_num_in_subtrees)|Organizes page tree nodes in a document into a balanced tree.<br/>            Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

