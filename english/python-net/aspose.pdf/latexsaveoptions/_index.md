---
title: LaTeXSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to TeX format.
type: docs
weight: 800
url: /python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

Save options for export to TeX format.

The LaTeXSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|LaTeXSaveOptions()|Initializes a new instance of the LaTeXSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|None|
|save_format|None|
|close_response|None|
|extract_ocr_sublayer_only|This atrribute turned on functionality for extracting image or text <br/>            for PDF documents with OCR sublayer.|
|try_merge_adjacent_same_background_images|Sometimes PDFs contain background images (of pages or table cells)<br/>              constructed from several same tiling background images put one near other.<br/>              In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates<br/>              visible boundaries beetween parts of background images,<br/>              cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader.<br/>               If it looks like exported document contains such visible boundaries between <br/>              parts of same background images, please try use this setting to get rid <br/>              of that unwanted effect. <br/>                ATTENTION! This optimization of quality usually essentially slows down conversion,<br/>              so, please, use this option only when it's really necessary.|
|out_directory_path|Property for|
|pages_count|Returns the number of pages after conversion.|
## Methods
| Name | Description |
| :- | :- |
|add_font_encs(font_encs)|Adds a font ancoding to the font encoding list|
|clear_font_encs()|Clears the font encoding list|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

