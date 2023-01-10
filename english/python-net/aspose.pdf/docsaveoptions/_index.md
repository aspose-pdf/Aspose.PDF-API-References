---
title: DocSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to Doc format
type: docs
weight: 220
url: /python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Save options for export to Doc format

The DocSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|DocSaveOptions()|Initializes a new instance of the DocSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.|
|save_format|Format of data save.|
|close_response|Gets or sets boolean value which indicates will Response object be closed after document saved into response.|
|extract_ocr_sublayer_only|This atrribute turned on functionality for extracting image or text <br/>            for PDF documents with OCR sublayer.|
|try_merge_adjacent_same_background_images|Sometimes PDFs contain background images (of pages or table cells)<br/>              constructed from several same tiling background images put one near other.<br/>              In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates<br/>              visible boundaries beetween parts of background images,<br/>              cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader.<br/>               If it looks like exported document contains such visible boundaries between <br/>              parts of same background images, please try use this setting to get rid <br/>              of that unwanted effect. <br/>                ATTENTION! This optimization of quality usually essentially slows down conversion,<br/>              so, please, use this option only when it's really necessary.|
|mode|Recognition mode.|
|relative_horizontal_proximity|In Pdf words may be innerly represented with operators that prints words<br/>              by independently printing their letters or syllables. So, to detect words sometimes we need detect groups<br/>              of independent chars that are in fact words.<br/>                This setting defines width of space between text elements(letters, syllables) <br/>              that must be treated as distance between words during recognition of words in source PDF.<br/>              (presence of empty space at least with this width between letters means that <br/>               textual elements pertain to different words).<br/>              It's normed to font size -  1.0 means 100% of supposed word's font size.<br/>             ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts<br/>             for which optimal value cannot be calculated from font. <br/>               So, in vast majority of cases this parameter changes nothing in result document.|
|max_distance_between_text_lines|This parameter is used for grouping text lines into paragraphs.<br/>            Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height.|
|recognize_bullets|Switch on the recognition of bullets|
|add_return_to_line_end|Use paragraph or line breaks|
|image_resolution_x|Converted images X resolution.|
|image_resolution_y|Converted images Y resolution.|
|format|Output format|
|batch_size|Defines batch size if batched conversion is applicable<br/>            to source and destination formats pair.|
|memory_save_mode_path|Defines the path (file name or directory name) to hold<br/>            temporary data when converting in memory save mode.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

