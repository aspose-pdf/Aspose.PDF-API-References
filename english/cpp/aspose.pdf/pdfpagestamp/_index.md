---
title: Aspose::Pdf::PdfPageStamp class
linktitle: PdfPageStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfPageStamp class. Class represents stamp which uses PDF page as stamp in C++.'
type: docs
weight: 12400
url: /cpp/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class


Class represents stamp which uses PDF page as stamp.

```cpp
class PdfPageStamp : public Aspose::Pdf::Stamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_Background](../stamp/get_background/)() const | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [get_BottomMargin](../stamp/get_bottommargin/)() const | Gets bottom margin of stamp. |
| virtual [get_Height](../stamp/get_height/)() | Desired height of the stamp on the page. |
| [get_HorizontalAlignment](../stamp/get_horizontalalignment/)() const | Gets Horizontal alignment of stamp on the page. |
| [get_LeftMargin](../stamp/get_leftmargin/)() const | Gets left margin of stamp. |
| [get_Opacity](../stamp/get_opacity/)() const | Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineOpacity](../stamp/get_outlineopacity/)() const | Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineWidth](../stamp/get_outlinewidth/)() const | Gets a value of the stamp outline width. By default the value is 1.0. |
| [get_PdfPage](./get_pdfpage/)() const | Gets page which will be used as stamp. |
| [get_RightMargin](../stamp/get_rightmargin/)() const | Gets right margin of stamp. |
| [get_Rotate](../stamp/get_rotate/)() | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [get_RotateAngle](../stamp/get_rotateangle/)() | Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [get_TopMargin](../stamp/get_topmargin/)() const | Gets top margin of stamp. |
| [get_VerticalAlignment](../stamp/get_verticalalignment/)() const | Gets vertical alignment of stamp on page. |
| virtual [get_Width](../stamp/get_width/)() | Desired width of the stamp on the page. |
| [get_XIndent](../stamp/get_xindent/)() const | Horizontal stamp coordinate, starting from the left. |
| [get_YIndent](../stamp/get_yindent/)() const | Vertical stamp coordinate, starting from the bottom. |
| [get_Zoom](../stamp/get_zoom/)() const | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [get_ZoomX](../stamp/get_zoomx/)() const | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [get_ZoomY](../stamp/get_zoomy/)() const | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [getStampId](../stamp/getstampid/)() | Returns stamp ID. |
| [PdfPageStamp](./pdfpagestamp/)(System::SharedPtr\<Page\>) | Constructor of [PdfPageStamp](./). |
| [PdfPageStamp](./pdfpagestamp/)(System::String, int32_t) | Creates [Pdf](../) page stamp from specifed page of the document in specified file. |
| [PdfPageStamp](./pdfpagestamp/)(System::SharedPtr\<System::IO::Stream\>, int32_t) | Creates [Pdf](../) page stamp from specifed page in the document from the stream. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Put stamp on the specified page. |
| [set_Background](../stamp/set_background/)(bool) | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [set_BottomMargin](../stamp/set_bottommargin/)(double) | Sets bottom margin of stamp. |
| virtual [set_Height](../stamp/set_height/)(double) | Desired height of the stamp on the page. |
| [set_HorizontalAlignment](../stamp/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets Horizontal alignment of stamp on the page. |
| [set_LeftMargin](../stamp/set_leftmargin/)(double) | Sets left margin of stamp. |
| [set_Opacity](../stamp/set_opacity/)(double) | Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineOpacity](../stamp/set_outlineopacity/)(double) | Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineWidth](../stamp/set_outlinewidth/)(double) | Sets a value of the stamp outline width. By default the value is 1.0. |
| [set_PdfPage](./set_pdfpage/)(System::SharedPtr\<Page\>) | Sets page which will be used as stamp. |
| [set_RightMargin](../stamp/set_rightmargin/)(double) | Sets right margin of stamp. |
| [set_Rotate](../stamp/set_rotate/)(Rotation) | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [set_RotateAngle](../stamp/set_rotateangle/)(double) | Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [set_TopMargin](../stamp/set_topmargin/)(double) | Sets top margin of stamp. |
| [set_VerticalAlignment](../stamp/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets vertical alignment of stamp on page. |
| virtual [set_Width](../stamp/set_width/)(double) | Desired width of the stamp on the page. |
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
