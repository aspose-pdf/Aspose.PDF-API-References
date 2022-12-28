---
title: ImageStamp
second_title: Aspose.PDF for Python via .NET API Reference
description: Reresents graphic stamp.
type: docs
weight: 690
url: /python-net/aspose.pdf/imagestamp/
---

## ImageStamp class

Reresents graphic stamp.

The ImageStamp type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ImageStamp(image)|Initializes a new instance of the ImageStamp class|
|ImageStamp(file_name)|Initializes a new instance of the ImageStamp class|
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
|width|Gets or sets image width. Setting this property allos to scal image horizontally.|
|height|Gets or sets image height. Setting this image allows to scale image vertically.|
|zoom_y|Vertical zooming factor of the stamp. Allows to scale stamp vertically.|
|zoom|Zooming factor of the stamp. Allows to scale stamp.<br/>            Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. <br/>            Setting of this property changes both ZoomX and ZoomY properties. <br/>            If ZoomX and ZoomY are different then Zoom property returns ZoomX value.|
|rotate_angle|Gets or sets rotate angle of stamp in degrees.<br/>            This property allows to set arbitrary rotate angle.|
|image|Gets image stream used for stamping.|
|quality|Gets or sets quality of image stamp in percent. Valid values are 0..100%.|
## Methods
| Name | Description |
| :- | :- |
|put(page)|Adds graphic stamp on the page.|
|set_stamp_id(value)|Sets stamp Id.|
|get_stamp_id()|Returns stamp ID.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

