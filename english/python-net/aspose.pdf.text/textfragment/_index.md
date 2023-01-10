---
title: TextFragment
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents fragment of Pdf text.
type: docs
weight: 390
url: /python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

Represents fragment of Pdf text.

The TextFragment type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextFragment()|Initializes new instance of the [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object.|
|TextFragment(tab_stops)|Initializes a new instance of the TextFragment class|
|TextFragment(text)|Initializes a new instance of the TextFragment class|
|TextFragment(text, tab_stops)|Initializes a new instance of the TextFragment class|
## Properties
| Name | Description |
| :- | :- |
|vertical_alignment|Gets or sets a vertical alignment of text fragment.|
|horizontal_alignment|Gets or sets a horizontal alignment of text fragment.|
|margin|Gets or sets a outer margin for paragraph (for pdf generation)|
|is_first_paragraph_in_column|Gets or sets a bool value that indicates whether this paragraph will be at next column.<br/>            Default is false.(for pdf generation)|
|is_kept_with_next|Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph.<br/>            Default is false.(for pdf generation)|
|is_in_new_page|Gets or sets a bool value that force this paragraph generates at new page.<br/>            Default is false.(for pdf generation)|
|is_in_line_paragraph|Gets or sets a paragraph is inline.<br/>            Default is false.(for pdf generation)|
|hyperlink|Sets the fragment hyperlink|
|z_index|Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex <br/>            will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative <br/>            ZIndex will be placed behind the text in the page.|
|replace_options|Gets text replace options. The options define behavior when fragment text is replaced to more short/long.|
|text|Gets or sets string text object that the [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object represents.|
|text_state|Gets or sets text state for the text that [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object represents.|
|segments|Gets text segments for current [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).|
|position|Gets or sets text position for text, represented with [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object.|
|baseline_position|Gets text position for text, represented with [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object.<br/>            The YIndent of the Position structure represents baseline coordinate of the text fragment.|
|rectangle|Gets rectangle of the TextFragment|
|page|Gets page that contains the TextFragment|
|form|Gets form object that contains the TextFragment|
|wrap_lines_count|Gets or sets wrap lines count for this paragraph(for pdf generation only)|
|end_note|Gets or sets the paragraph end note.(for pdf generation only)|
|foot_note|Gets or sets the paragraph foot note.(for pdf generation only)|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clone the fragment.|
|isolate_text_segments(start_index, length)|Gets [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) representing specified part of the [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) text.|
|clone_with_segments()|Clone the fragment with all segments.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

