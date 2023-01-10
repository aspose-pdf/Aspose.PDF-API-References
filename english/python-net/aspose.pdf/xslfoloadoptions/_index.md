---
title: XslFoLoadOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents options for loading/importing XSL-FO file into pdf document.
type: docs
weight: 1820
url: /python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

Represents options for loading/importing XSL-FO file into pdf document.

The XslFoLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|XslFoLoadOptions()|Creates [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) object without xsl data.|
|XslFoLoadOptions(xsl_file)|Initializes a new instance of the XslFoLoadOptions class|
|XslFoLoadOptions(xsl_stream)|Initializes a new instance of the XslFoLoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.|
|load_format|Represents file format which [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) describes.|
|xsl_stream|Gets xsl data for converting xml into pdf document.|
|base_path|The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file.|
|parsing_errors_handling_type|Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

