---
title: Aspose::Pdf::ImageStamp class
linktitle: ImageStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ImageStamp class. Reresents graphic stamp in C++.'
type: docs
weight: 6700
url: /cpp/aspose.pdf/imagestamp/
---
## ImageStamp class


Reresents graphic stamp.

```cpp
class ImageStamp : public Aspose::Pdf::Stamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_AlternativeText](./get_alternativetext/)() const | Gets Alternative [Text](../../aspose.pdf.text/) for image stamp. |
| [get_Background](../stamp/get_background/)() const | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [get_BottomMargin](../stamp/get_bottommargin/)() const | Gets bottom margin of stamp. |
| [get_Height](./get_height/)() override | Gets image height. Setting this image allows to scale image vertically. |
| [get_HorizontalAlignment](../stamp/get_horizontalalignment/)() const | Gets Horizontal alignment of stamp on the page. |
| [get_Image](./get_image/)() const | Gets image stream used for stamping. |
| [get_LeftMargin](../stamp/get_leftmargin/)() const | Gets left margin of stamp. |
| [get_Opacity](../stamp/get_opacity/)() const | Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineOpacity](../stamp/get_outlineopacity/)() const | Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineWidth](../stamp/get_outlinewidth/)() const | Gets a value of the stamp outline width. By default the value is 1.0. |
| [get_Quality](./get_quality/)() const | Gets quality of image stamp in percent. Valid values are 0..100%. |
| [get_RightMargin](../stamp/get_rightmargin/)() const | Gets right margin of stamp. |
| [get_Rotate](../stamp/get_rotate/)() | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [get_RotateAngle](../stamp/get_rotateangle/)() | Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [get_TopMargin](../stamp/get_topmargin/)() const | Gets top margin of stamp. |
| [get_VerticalAlignment](../stamp/get_verticalalignment/)() const | Gets vertical alignment of stamp on page. |
| [get_Width](./get_width/)() override | Gets image width. Setting this property allos to scal image horizontally. |
| [get_XIndent](../stamp/get_xindent/)() const | Horizontal stamp coordinate, starting from the left. |
| [get_YIndent](../stamp/get_yindent/)() const | Vertical stamp coordinate, starting from the bottom. |
| [get_Zoom](../stamp/get_zoom/)() const | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [get_ZoomX](../stamp/get_zoomx/)() const | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [get_ZoomY](../stamp/get_zoomy/)() const | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [getStampId](../stamp/getstampid/)() | Returns stamp ID. |
| [ImageStamp](./imagestamp/)(System::SharedPtr\<System::IO::Stream\>) | Initializes a new instance of the [ImageStamp](./) class. |
| [ImageStamp](./imagestamp/)(System::String) | Creates image stamp by image in the specified file. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Adds graphic stamp on the page. |
| [set_AlternativeText](./set_alternativetext/)(System::String) | Sets Alternative [Text](../../aspose.pdf.text/) for image stamp. |
| [set_Background](../stamp/set_background/)(bool) | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [set_BottomMargin](../stamp/set_bottommargin/)(double) | Sets bottom margin of stamp. |
| [set_Height](./set_height/)(double) override | Sets image height. Setting this image allows to scale image vertically. |
| [set_HorizontalAlignment](../stamp/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets Horizontal alignment of stamp on the page. |
| [set_LeftMargin](../stamp/set_leftmargin/)(double) | Sets left margin of stamp. |
| [set_Opacity](../stamp/set_opacity/)(double) | Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineOpacity](../stamp/set_outlineopacity/)(double) | Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineWidth](../stamp/set_outlinewidth/)(double) | Sets a value of the stamp outline width. By default the value is 1.0. |
| [set_Quality](./set_quality/)(int32_t) | Sets quality of image stamp in percent. Valid values are 0..100%. |
| [set_RightMargin](../stamp/set_rightmargin/)(double) | Sets right margin of stamp. |
| [set_Rotate](../stamp/set_rotate/)(Rotation) | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [set_RotateAngle](../stamp/set_rotateangle/)(double) | Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [set_TopMargin](../stamp/set_topmargin/)(double) | Sets top margin of stamp. |
| [set_VerticalAlignment](../stamp/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets vertical alignment of stamp on page. |
| [set_Width](./set_width/)(double) override | Sets image width. Setting this property allos to scal image horizontally. |
| [set_XIndent](../stamp/set_xindent/)(double) | Horizontal stamp coordinate, starting from the left. |
| [set_YIndent](../stamp/set_yindent/)(double) | Vertical stamp coordinate, starting from the bottom. |
| [set_Zoom](../stamp/set_zoom/)(double) | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [set_ZoomX](../stamp/set_zoomx/)(double) | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [set_ZoomY](../stamp/set_zoomy/)(double) | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [setStampId](../stamp/setstampid/)(int32_t) | Sets stamp [Id](../id/). |
| [Stamp](../stamp/stamp/)() |  |
## See Also

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
