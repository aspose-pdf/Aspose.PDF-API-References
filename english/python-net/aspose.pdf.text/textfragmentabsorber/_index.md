---
title: TextFragmentAbsorber
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents an absorber object of text fragments.<br/>            Performs text search and provides access to search results via [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) collection.
type: docs
weight: 400
url: /python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Represents an absorber object of text fragments.<br/>            Performs text search and provides access to search results via [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) collection.

The TextFragmentAbsorber type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextFragmentAbsorber()|Initializes a new instance of the [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) that performs search of all text segments of the document or page.|
|TextFragmentAbsorber(text_edit_options)|Initializes a new instance of the TextFragmentAbsorber class|
|TextFragmentAbsorber(phrase)|Initializes a new instance of the TextFragmentAbsorber class|
|TextFragmentAbsorber(phrase, text_search_options)|Initializes a new instance of the TextFragmentAbsorber class|
|TextFragmentAbsorber(phrase, text_search_options, text_edit_options)|Initializes a new instance of the TextFragmentAbsorber class|
|TextFragmentAbsorber(phrase, text_edit_options)|Initializes a new instance of the TextFragmentAbsorber class|
## Properties
| Name | Description |
| :- | :- |
|text|Gets extracted text that the [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extracts on the PDF document or page.|
|has_errors|Value indicates whether errors were found during text extraction.<br/>            Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.|
|errors|List of [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) objects. It contain information about errors were found during text extraction.<br/>            Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.|
|extraction_options|Gets or sets text extraction options.|
|text_search_options|Gets or sets search options. The options enable search using regular expressions.|
|text_fragments|Gets collection of search occurrences that are presented with [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) objects.|
|phrase|Gets or sets phrase that the [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) searches on the PDF document or page.|
|text_edit_options|Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font.|
|text_replace_options|Gets or sets text replace options. The options define behavior when fragment text is replaced to more short/long.|
## Methods
| Name | Description |
| :- | :- |
|visit(page)|Performs search on the specified page.|
|visit(pdf)|Performs search on the specified document.|
|visit(x_form)|Performs search on the specified form object.|
|apply_for_all_fragments(font)|Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.|
|apply_for_all_fragments(font_size)|Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.|
|apply_for_all_fragments(font, font_size)|Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.|
|remove_all_text(page)|Removes all text from the specified page.|
|remove_all_text(page, rect)|Removes text inside the specified rectangle from the specified page.|
|remove_all_text(document)|Removes all text from the document.|
|reset()|Clears TextFragments collection of this [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) object.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

