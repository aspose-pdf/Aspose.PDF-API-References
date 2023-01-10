---
title: SvgLoadOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents options for loading/importing SVG file into pdf document.
type: docs
weight: 1450
url: /python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Represents options for loading/importing SVG file into pdf document.

The SvgLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|SvgLoadOptions()|Initializes a new instance of the SvgLoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.|
|load_format|Represents file format which [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) describes.|
|page_info|Gets or sets page info that should be applied during loading of document.<br/>            NOTE that this parameter only works when ConversionEngine == ConversionEngines.NewEngine|
|adjust_page_size|Adust pdf page size to svg size|
|conversion_engine|Allows select conversion engine that will be in use during conversion.<br/>            Currently new engine is in B-testing stage, so this value by default set to <br/>            ConversionEngines.LegacyEngine|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

