---
title: TextStamp
second_title: Aspose.PDF for Python via .NET API Reference
description: Reresents textual stamp.
type: docs
weight: 1550
url: /python-net/aspose.pdf/textstamp/
---

## TextStamp class

Reresents textual stamp.

The TextStamp type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextStamp(value)|Initializes a new instance of the TextStamp class|
|TextStamp(value, text_state)|Initializes a new instance of the TextStamp class|
|TextStamp(formatted_text)|Initializes a new instance of the TextStamp class|
## Properties
| Name | Description |
| :- | :- |
|background|Sets or gets a bool value that indicates the content is stamped as background.<br/>            If the value is true, the stamp content is layed at the bottom.<br/>            By defalt, the value is false, the stamp content is layed at the top.|
|opacity|Gets or sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0.<br/>            By default the value is 1.0.|
|outline_opacity|Gets or sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0.<br/>            By default the value is 1.0.|
|outline_width|Gets or sets a value of the stamp outline width.<br/>            By default the value is 1.0.|
|rotate|Sets or gets the rotation of stamp content according [Rotation](/pdf/python-net/aspose.pdf/rotation/) values.<br/>            Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees).<br/>            To set arbitrary angle use RotateAngle property. <br/>            If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.|
|x_indent|Horizontal stamp coordinate, starting from the left.|
|y_indent|Vertical stamp coordinate, starting from the bottom.|
|horizontal_alignment|Gets or sets Horizontal alignment of stamp on the page.|
|vertical_alignment|Gets or sets vertical alignment of stamp on page.|
|left_margin|Gets or sets left margin of stamp.|
|right_margin|Gets or sets right margin of stamp.|
|bottom_margin|Gets or sets bottom margin of stamp.|
|top_margin|Gets or sets top margin of stamp.|
|zoom_x|Horizontal zooming factor of the stamp. Allows to scale stamp horizontally.|
|width|Desired width of the stamp on the page.|
|height|Desired height of the stamp on the page.|
|zoom_y|Vertical zooming factor of the stamp. Allows to scale stamp vertically.|
|zoom|Zooming factor of the stamp. Allows to scale stamp.<br/>            Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. <br/>            Setting of this property changes both ZoomX and ZoomY properties. <br/>            If ZoomX and ZoomY are different then Zoom property returns ZoomX value.|
|rotate_angle|Gets or sets rotate angle of stamp in degrees.<br/>            This property allows to set arbitrary rotate angle.|
|draw|This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.|
|treat_y_indent_as_base_line|Defines coordinate origin for placing text.<br/>            If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line.<br/>            If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.|
|word_wrap|Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.|
|justify|Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.|
|scale|Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.|
|value|Gets or sets string value which is used as stamp on the page.|
|text_state|Gets text properties of the stamp. See [text_state](/pdf/python-net/aspose.pdf/textstamp/) for details.|
|text_alignment|Alignment of the text inside the stamp.|
|max_row_width|Max row height for WordWrap option.|
## Methods
| Name | Description |
| :- | :- |
|put(page)|Adds textual stamp on the page.|
|set_stamp_id(value)|Sets stamp Id.|
|get_stamp_id()|Returns stamp ID.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

