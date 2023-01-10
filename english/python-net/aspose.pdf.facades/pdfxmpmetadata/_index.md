---
title: PdfXmpMetadata
second_title: Aspose.PDF for Python via .NET API Reference
description: Class for manipulation with XMP metadata.
type: docs
weight: 380
url: /python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Class for manipulation with XMP metadata.

The PdfXmpMetadata type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfXmpMetadata()|Constructor for PdfXmpMetadata.|
|PdfXmpMetadata(document)|Initializes a new instance of the PdfXmpMetadata class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|keys|Gets keys from the dictionary.|
|values|Gets the collection of values in dictionary.|
|is_fixed_size|Returns true is collection has fixed size.|
|is_synchronized|Returns true if collection is synchronized.|
|sync_root|Gets synchroniztion object of the collection.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves the PDF document to the specified file.|
|save(dest_stream)|Saves the PDF document to the specified stream.|
|add(key, value)|Adds value to XMP metadata.|
|add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description)|Adds extension field into metadata.|
|add(key, value)|Adds new element to the dictionary object.|
|add(key, value)|Adds extension field into metadata.|
|remove(key)|Removes element with specified key.|
|remove(key)|Removes key from the dictionary.|
|contains(key)|Checks if dictionary contains the specified key.|
|contains(property)|Checks if dictionary contains the specified property.|
|get_xmp_metadata()|Get the XmpMetadata of the input pdf in a xml format.|
|get_xmp_metadata(name)|Get a part of the XmpMetadata of the input pdf according to a meta name.|
|close()|Releases any resources associates with the current facade.|
|register_namespace_uri(prefix, namespace_uri)|Registers the namespace URI.|
|get_namespace_uri_by_prefix(prefix)|Gets namespace URI by prefix.|
|get_prefix_by_namespace_uri(namespace_uri)|Gets the prefix by namespace URI.|
|contains_key(key)|Determines does this dictionary contasins specified key.|
|try_get_value(key, value)|Tries to find key in the dictionary and retreives value if found.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

