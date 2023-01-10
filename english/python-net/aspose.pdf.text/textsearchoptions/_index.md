---
title: TextSearchOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents text search options
type: docs
weight: 460
url: /python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Represents text search options

The TextSearchOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextSearchOptions(is_regular_expression_used)|Initializes a new instance of the TextSearchOptions class|
|TextSearchOptions(rectangle)|Initializes a new instance of the TextSearchOptions class|
|TextSearchOptions(rectangle, is_regular_expression_used)|Initializes a new instance of the TextSearchOptions class|
## Properties
| Name | Description |
| :- | :- |
|is_regular_expression_used|Gets or sets indication that regular expression is used.|
|limit_to_page_bounds|Gets or sets indication that text is searched within the page bounds.|
|rectangle|Gets or sets rectangle that bounds the searched text.|
|use_font_engine_encoding|Gets or sets indication that text will be searched using font engine encoding.<br/>            true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document)<br/>            false - means that document font encoding will be used (default value)|
|ignore_shadow_text|Gets or sets indication that text fragments representing shadow of normal text will be ignored during search.<br/>            true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions)<br/>            false - means that shadow text will be found as well as normal text (default value)|
|log_text_extraction_errors|Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber.<br/>            true - means that text extraction (decoding) errors will be loged. It may decrease performance.<br/>            false (default) - no error loging.|
|ignore_resource_font_errors|Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber.<br/>            true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing.<br/>            false (default) - absence of font error will terminate processing by throwing exception.|
|search_for_text_related_graphics|Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search.<br/>            true - searching for text related graphics will be performed (default value).<br/>            false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping.|
|stored_graphic_elements_max_count|Gets or sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements.<br/>            The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found.|
|search_in_annotations|Gets or sets value that permits searching for text in Annotations.<br/>            true - text will be searched in Annotations.<br/>            false - text in Annotations won't be parsed by TextFragmentAbsorber.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

