---
title: TextEditOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Descubes options of text edit operations.
type: docs
weight: 340
url: /python-net/aspose.pdf.text/texteditoptions/
---

## TextEditOptions class

Descubes options of text edit operations.

The TextEditOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextEditOptions(no_character_behavior)|Initializes a new instance of the TextEditOptions class|
|TextEditOptions(font_replace_behavior)|Initializes a new instance of the TextEditOptions class|
|TextEditOptions(allow_language_transformation)|Initializes a new instance of the TextEditOptions class|
|TextEditOptions(language_transformation_behavior)|Initializes a new instance of the TextEditOptions class|
## Properties
| Name | Description |
| :- | :- |
|replacement_font|Gets or sets font used for replacing if user font does not contain required character|
|no_character_behavior|Gets or sets mode that defines behavior in case fonts don't contain requested characters.|
|font_replace_behavior|Gets mode that defines behavior for fonts replacement scenarios.|
|allow_language_transformation|Gets or sets value that permits usage of language transformation during adding or editing of text.<br/>            true - language transformation will be applied if necessary (default value).<br/>            false - language transformation will NOT be applied.|
|language_transformation_behavior|Gets mode that defines behavior for language transformation scenarios.|
|clipping_paths_processing|Gets mode for processing clipping path of the edited text.|
|to_attempt_get_underline_from_source|Gets or sets value that permits searching for text underlining on the page of source document.<br/>            (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

