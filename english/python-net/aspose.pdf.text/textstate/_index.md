---
title: TextState
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a text state of a text
type: docs
weight: 490
url: /python-net/aspose.pdf.text/textstate/
---

## TextState class

Represents a text state of a text

The TextState type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextState()|Creates text state object.|
|TextState(font_size)|Initializes a new instance of the TextState class|
|TextState(foreground_color)|Initializes a new instance of the TextState class|
|TextState(foreground_color, font_size)|Initializes a new instance of the TextState class|
|TextState(font_family)|Initializes a new instance of the TextState class|
|TextState(font_family, bold, italic)|Initializes a new instance of the TextState class|
|TextState(font_family, font_size)|Initializes a new instance of the TextState class|
## Properties
| Name | Description |
| :- | :- |
|character_spacing|Gets or sets character spacing of the text.|
|line_spacing|Gets or sets line spacing of the text.|
|horizontal_scaling|Gets or sets horizontal scaling of the text.|
|subscript|Gets or sets subscript of the text.|
|superscript|Gets or sets superscript of the text.|
|word_spacing|Gets or sets word spacing of the text.|
|invisible|Gets or sets the invisibility of text. This basically reflects the [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/) state, except for some special cases (like clipping).|
|rendering_mode|Gets or sets rendering mode of text.|
|font_size|Gets or sets font size of the text.|
|font|Gets or sets font of the text.|
|foreground_color|Gets or sets foreground color of the text.|
|stroking_color|Gets or sets foreground color of the text.|
|underline|Gets or sets underline for the text, represented by the [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object|
|strike_out|Sets strikeout for the text, represented by the [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) object|
|background_color|Sets background color of the text.|
|font_style|Sets font style of the text.|
|horizontal_alignment|Gets or sets horizontal alignment for the text.|
|TAB_TAG|You can place this tag in text to declare tabulation.|
|TABSTOP_DEFAULT_VALUE|Default value of tabulation in widths of space character of default font.|
## Methods
| Name | Description |
| :- | :- |
|apply_changes_from(text_state)|Applies settings from another textState.|
|measure_string(str)|Measures the string.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

