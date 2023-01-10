---
title: PdfSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to Pdf format
type: docs
weight: 1240
url: /python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

Save options for export to Pdf format

The PdfSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfSaveOptions()|Initializes a new instance of the PdfSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.|
|save_format|Format of data save.|
|close_response|Gets or sets boolean value which indicates will Response object be closed after document saved into response.|
|temp_path|Path for temporary files.|
|default_font_name|Font name used by default for fonts which are absent on computer.<br/>            When the PDF document that is saved into PDF contains fonts, that are not available <br/>            in the document itself and on the device, API replaces this fonts with the <br/>            default font(if font with [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) is found on device)|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

