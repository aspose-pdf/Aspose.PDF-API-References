---
title: SvgSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to SVG format
type: docs
weight: 1460
url: /python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Save options for export to SVG format

The SvgSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|SvgSaveOptions()|Initializes a new instance of the SvgSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.|
|save_format|Format of data save.|
|close_response|Gets or sets boolean value which indicates will Response object be closed after document saved into response.|
|extract_ocr_sublayer_only|None|
|try_merge_adjacent_same_background_images|None|
|treat_target_file_name_as_directory|This options defines whether will be created target directory<br/>             (if absent yet) with same name as requested output file <br/>             instead of requested output file itself.<br/>             It so, that directory will contain all output SVG-images of pages (like described below).<br/>               If no, output files of pages other then first one will be created exactly in requested directory<br/>            as main output file, but will contain in file name suffix _[2...n], that<br/>             is defined by page number, f.e. if You define output file "C:\AsposeTests\output.svg"<br/>             and output will contain several svg-files of pages,<br/>             then files of pages will be created also in directory "C:\AsposeTests\" and have names 'output.svg', 'output_2.svg', 'output_3.svg' etc.|
|compress_output_to_zip_archive|Specifies whether output will be created as one zip-archive.<br/>             Please refer comment to 'TreatTargetFileNameAsDirectory' options to see rules of naming<br/>             of svg-files of pages for multipage source document, that are also applied to zipped set of output files.|
|scale_to_pixels|Specifies whether to scale the output document from typographic points to pixels.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

