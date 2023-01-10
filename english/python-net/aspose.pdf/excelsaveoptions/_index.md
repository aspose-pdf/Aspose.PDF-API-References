---
title: ExcelSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to Excel format
type: docs
weight: 330
url: /python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Save options for export to Excel format

The ExcelSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ExcelSaveOptions()|Initializes a new instance of the ExcelSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.|
|save_format|Format of data save.|
|close_response|Gets or sets boolean value which indicates will Response object be closed after document saved into response.|
|extract_ocr_sublayer_only|This atrribute turned on functionality for extracting image or text <br/>            for PDF documents with OCR sublayer.|
|try_merge_adjacent_same_background_images|Sometimes PDFs contain background images (of pages or table cells)<br/>              constructed from several same tiling background images put one near other.<br/>              In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates<br/>              visible boundaries beetween parts of background images,<br/>              cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader.<br/>               If it looks like exported document contains such visible boundaries between <br/>              parts of same background images, please try use this setting to get rid <br/>              of that unwanted effect. <br/>                ATTENTION! This optimization of quality usually essentially slows down conversion,<br/>              so, please, use this option only when it's really necessary.|
|minimize_the_number_of_worksheets|Set true if you need to minimize the number of worksheets in resultant workbook.<br/>            Default value is false; it means save of each PDF page as separated worksheet.|
|insert_blank_column_at_first|Set true if you need inserting of blank column as the first column of worksheet.<br/>            Default value is false; it means that blank column will not be inserted.|
|uniform_worksheets|Set true for using uniform columns division through the document. <br/>            Default value is false; it means that columns division will independent for each page.|
|format|Output format|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

