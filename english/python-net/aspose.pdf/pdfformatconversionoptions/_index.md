---
title: PdfFormatConversionOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: represents set of options for convert PDF document
type: docs
weight: 1220
url: /python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

represents set of options for convert PDF document

The PdfFormatConversionOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFormatConversionOptions(output_log_file_name, format, action)|Initializes a new instance of the PdfFormatConversionOptions class|
|PdfFormatConversionOptions(output_log_file_name, format)|Initializes a new instance of the PdfFormatConversionOptions class|
|PdfFormatConversionOptions(format)|Initializes a new instance of the PdfFormatConversionOptions class|
|PdfFormatConversionOptions(format, action)|Initializes a new instance of the PdfFormatConversionOptions class|
|PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action)|Initializes a new instance of the PdfFormatConversionOptions class|
|PdfFormatConversionOptions(output_log_stream, format, action)|Initializes a new instance of the PdfFormatConversionOptions class|
## Properties
| Name | Description |
| :- | :- |
|is_async_image_streams_conversion_mode|Gets/sets run of image streams in async mode.|
|is_low_memory_mode|Is low memory conversion mode enabled|
|format|PDF format.|
|log_file_name|Path to file where comments will be stored.|
|log_stream|Stream where comments will be stored.|
|error_action|Action for objects that can not be converted|
|transparency_action|Action for image masked objects|
|convert_soft_mask_action|Action for images with soft mask.|
|default|Gets PdfFormatConversionOptions object with default parameters|
|non_specification_cases|Holds flags to control PDF/A conversion process for cases when source document<br/>            doesn't correspond to PDF/A specification.|
|symbolic_font_encoding_strategy|Strategy to copy encoding data for symbolic fonts if symbolic TrueType font<br/>            has more than one encoding subtable.|
|align_text|This flag controls text alignment in converted document. By default document conversion <br/>            doesn't affect text alignment and leave text as is. But in some cases font substitution<br/>            causes text overlapping or extra spaces in converted document. When  this flag is set<br/>            special alignment operations will be performed. This flag should be set only for documents<br/>            which have problems with overlapped text or extra text spaces cause using of this flag decrease<br/>            performance and in some cases could corrupt text content.|
|pua_text_processing_strategy|Strategy to process symbols from unicode Private Use Area (PUA).|
|optimize_file_size|Gets or sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size.<br/>            Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag <br/>            also will be used to switch on optimization for another data structures, such as graphic.  <br/>            Set of this flag and mode could significantly reduce file size but at the same time it could<br/>            significantly decrease performance of conversion.|
|exclude_fonts_strategy|Strategy(ies) to exclude superfluous fonts and reduce document file size. <br/>            This parameter has sense only when flag [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) is set to true.<br/>            By default combination of strategies [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) and<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) is used.|
|font_embedding_options|Options for cases when it's not possible to embed some fonts into PDF document.|
|unicode_processing_rules|Rules to solve problems with unicode mapping. Can be null.|
|icc_profile_file_name|Gets or sets the filename of icc profile name. In case of null the default icc profile used.|
|not_accessible_fonts|This property is out-property. It holds all the fonts(font names) which were not found on computer <br/>            at last PDF/A conversion.|
|is_transfer_info|Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default.|
|align_strategy|Strategy to align text. This parameter has sense only when flag [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)  is set to true.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

