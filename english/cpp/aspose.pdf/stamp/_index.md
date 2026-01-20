---
title: Aspose::Pdf::Stamp class
linktitle: Stamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Stamp class. An abstract class for various kinds of stamps which come as descendants in C++.'
type: docs
weight: 17400
url: /cpp/aspose.pdf/stamp/
---
## Stamp class


An abstract class for various kinds of stamps which come as descendants.

```cpp
class Stamp : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Background](./get_background/)() const | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [get_BottomMargin](./get_bottommargin/)() const | Gets bottom margin of stamp. |
| virtual [get_Height](./get_height/)() | Desired height of the stamp on the page. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Gets Horizontal alignment of stamp on the page. |
| [get_LeftMargin](./get_leftmargin/)() const | Gets left margin of stamp. |
| [get_Opacity](./get_opacity/)() const | Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineOpacity](./get_outlineopacity/)() const | Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineWidth](./get_outlinewidth/)() const | Gets a value of the stamp outline width. By default the value is 1.0. |
| [get_RightMargin](./get_rightmargin/)() const | Gets right margin of stamp. |
| [get_Rotate](./get_rotate/)() | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [get_RotateAngle](./get_rotateangle/)() | Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [get_TopMargin](./get_topmargin/)() const | Gets top margin of stamp. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Gets vertical alignment of stamp on page. |
| virtual [get_Width](./get_width/)() | Desired width of the stamp on the page. |
| virtual [get_XIndent](./get_xindent/)() | Horizontal stamp coordinate, starting from the left. |
| virtual [get_YIndent](./get_yindent/)() | Vertical stamp coordinate, starting from the bottom. |
| [get_Zoom](./get_zoom/)() const | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [get_ZoomX](./get_zoomx/)() const | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [get_ZoomY](./get_zoomy/)() const | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [getStampId](./getstampid/)() | Returns stamp ID. |
| virtual [Put](./put/)(System::SharedPtr\<Page\>) | Adds stamp on the page. |
| [set_Background](./set_background/)(bool) | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [set_BottomMargin](./set_bottommargin/)(double) | Sets bottom margin of stamp. |
| virtual [set_Height](./set_height/)(double) | Desired height of the stamp on the page. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets Horizontal alignment of stamp on the page. |
| [set_LeftMargin](./set_leftmargin/)(double) | Sets left margin of stamp. |
| [set_Opacity](./set_opacity/)(double) | Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineOpacity](./set_outlineopacity/)(double) | Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineWidth](./set_outlinewidth/)(double) | Sets a value of the stamp outline width. By default the value is 1.0. |
| [set_RightMargin](./set_rightmargin/)(double) | Sets right margin of stamp. |
| [set_Rotate](./set_rotate/)(Rotation) | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [set_RotateAngle](./set_rotateangle/)(double) | Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [set_TopMargin](./set_topmargin/)(double) | Sets top margin of stamp. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets vertical alignment of stamp on page. |
| virtual [set_Width](./set_width/)(double) | Desired width of the stamp on the page. |
| virtual [set_XIndent](./set_xindent/)(double) | Horizontal stamp coordinate, starting from the left. |
| virtual [set_YIndent](./set_yindent/)(double) | Vertical stamp coordinate, starting from the bottom. |
| [set_Zoom](./set_zoom/)(double) | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [set_ZoomX](./set_zoomx/)(double) | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [set_ZoomY](./set_zoomy/)(double) | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [setStampId](./setstampid/)(int32_t) | Sets stamp [Id](../id/). |
| [Stamp](./stamp/)() |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
