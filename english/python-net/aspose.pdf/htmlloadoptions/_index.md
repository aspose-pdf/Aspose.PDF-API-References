---
title: HtmlLoadOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents options for loading/importing html file into pdf document.
type: docs
weight: 480
url: /python-net/aspose.pdf/htmlloadoptions/
---

## HtmlLoadOptions class

Represents options for loading/importing html file into pdf document.

The HtmlLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|HtmlLoadOptions()|Creates load options for converting html into pdf document with empty base path.|
|HtmlLoadOptions(base_path)|Initializes a new instance of the HtmlLoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.|
|load_format|Represents file format which [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) describes.|
|is_render_to_single_page|Gets or sets rendering all document to single page|
|is_embed_fonts|Gets or sets fonts embedding to result document|
|page_layout_option|Gets or sets layout option.|
|html_media_type|Gets or sets possible media types used during rendering.|
|input_encoding|Gets or sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute.|
|base_path|The base path/url for the html file.|
|page_info|Gets or sets document page info|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

