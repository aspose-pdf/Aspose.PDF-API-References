---
title: EpubLoadOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Contains options for loading/importing EPUB file into pdf document.
type: docs
weight: 310
url: /python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Contains options for loading/importing EPUB file into pdf document.

The EpubLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|EpubLoadOptions()|Creates default load options for converting EPUB file into pdf document. <br/>            Default pdf page size - A4 300dpi 2480 X 3508.|
|EpubLoadOptions(page_size)|Initializes a new instance of the EpubLoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.|
|load_format|Represents file format which [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) describes.|
|page_size|Gets or sets output page size for import.|
|margin|Gets reference on object that represent marging info.|
|margins_area_usage_mode|Represents mode of usage of margins area - defines treatement <br/>              of instructions (if any) of CSS of imported document<br/>              related to usage of margins.|
|page_size_adjustment_mode|ATTENTION! The feature implemented but did not put yet to public API since blocker issue in <br/>              OSHARED layer revealed for sample document.<br/>              <br/>             <br/>              Represents mode of usage of page size during conversion.<br/>             Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required<br/>             pagesize. But sometimes content has specified horizontal positions or size that <br/>             does not allow put content into required page size.<br/>               In such case we can define what should be done in this case (i.e when size of content does not fit <br/>             required initial page size of result PDF document).|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

