---
title: Aspose::Pdf::PageNumberStamp class
linktitle: PageNumberStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageNumberStamp class. Represents page number stamp and used to number pages in C++.'
type: docs
weight: 11700
url: /cpp/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class


Represents page number stamp and used to number pages.

```cpp
class PageNumberStamp : public Aspose::Pdf::TextStamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_Background](../stamp/get_background/)() const | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [get_BottomMargin](../stamp/get_bottommargin/)() const | Gets bottom margin of stamp. |
| [get_Draw](../textstamp/get_draw/)() const | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [get_Format](./get_format/)() const | String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [get_Height](../textstamp/get_height/)() override | Desired height of the stamp on the page. |
| [get_HorizontalAlignment](../stamp/get_horizontalalignment/)() const | Gets Horizontal alignment of stamp on the page. |
| [get_Justify](../textstamp/get_justify/)() | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [get_LeftMargin](../stamp/get_leftmargin/)() const | Gets left margin of stamp. |
| [get_MaxRowWidth](../textstamp/get_maxrowwidth/)() const | Max row height for WordWrap option. |
| [get_NoCharacterBehavior](../textstamp/get_nocharacterbehavior/)() const | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [get_NumberingStyle](./get_numberingstyle/)() const | Numbering style which used by this stamp. |
| [get_Opacity](../stamp/get_opacity/)() const | Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineOpacity](../stamp/get_outlineopacity/)() const | Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [get_OutlineWidth](../stamp/get_outlinewidth/)() const | Gets a value of the stamp outline width. By default the value is 1.0. |
| [get_ReplacementFont](../textstamp/get_replacementfont/)() const | Gets font used for replacing if user font does not contain required character. |
| [get_RightMargin](../stamp/get_rightmargin/)() const | Gets right margin of stamp. |
| [get_Rotate](../stamp/get_rotate/)() | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [get_RotateAngle](../stamp/get_rotateangle/)() | Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [get_Scale](../textstamp/get_scale/)() const | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [get_StartingNumber](./get_startingnumber/)() const | Gets value of the number of starting page. Other pages will be numbered starting from this value. |
| [get_TextAlignment](../textstamp/get_textalignment/)() const | Alignment of the text inside the stamp. |
| [get_TextState](../textstamp/get_textstate/)() const | Gets text properties of the stamp. See **TextState** for details. |
| [get_TopMargin](../stamp/get_topmargin/)() const | Gets top margin of stamp. |
| [get_TreatYIndentAsBaseLine](../textstamp/get_treatyindentasbaseline/)() const | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [get_Value](../textstamp/get_value/)() | Gets string value which is used as stamp on the page. |
| [get_VerticalAlignment](../stamp/get_verticalalignment/)() const | Gets vertical alignment of stamp on page. |
| [get_Width](../textstamp/get_width/)() override | Desired width of the stamp on the page. |
| [get_WordWrap](../textstamp/get_wordwrap/)() const | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [get_WordWrapMode](../textstamp/get_wordwrapmode/)() const | Gets the word wrap mode for text rendering. |
| [get_XIndent](../stamp/get_xindent/)() const | Horizontal stamp coordinate, starting from the left. |
| [get_YIndent](../stamp/get_yindent/)() const | Vertical stamp coordinate, starting from the bottom. |
| [get_Zoom](../stamp/get_zoom/)() const | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [get_ZoomX](../stamp/get_zoomx/)() const | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [get_ZoomY](../stamp/get_zoomy/)() const | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [getStampId](../stamp/getstampid/)() | Returns stamp ID. |
| [PageNumberStamp](./pagenumberstamp/)(System::String) | Initializes a new instance of the [PageNumberStamp](./) class. |
| [PageNumberStamp](./pagenumberstamp/)() | Initializes a new instance of the [PageNumberStamp](./) class. Format is set to "#". |
| [PageNumberStamp](./pagenumberstamp/)(System::SharedPtr\<Facades::FormattedText\>) | Creates [PageNumberStamp](./) by formatted text. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Adds page number. |
| [set_Background](../stamp/set_background/)(bool) | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [set_BottomMargin](../stamp/set_bottommargin/)(double) | Sets bottom margin of stamp. |
| [set_Draw](../textstamp/set_draw/)(bool) | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [set_Format](./set_format/)(System::String) | String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [set_Height](../textstamp/set_height/)(double) override | Desired height of the stamp on the page. |
| [set_HorizontalAlignment](../stamp/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets Horizontal alignment of stamp on the page. |
| [set_Justify](../textstamp/set_justify/)(bool) | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [set_LeftMargin](../stamp/set_leftmargin/)(double) | Sets left margin of stamp. |
| [set_MaxRowWidth](../textstamp/set_maxrowwidth/)(double) | Max row height for WordWrap option. |
| [set_NoCharacterBehavior](../textstamp/set_nocharacterbehavior/)(TextStamp::NoCharacterAction) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Numbering style which used by this stamp. |
| [set_Opacity](../stamp/set_opacity/)(double) | Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineOpacity](../stamp/set_outlineopacity/)(double) | Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [set_OutlineWidth](../stamp/set_outlinewidth/)(double) | Sets a value of the stamp outline width. By default the value is 1.0. |
| [set_ReplacementFont](../textstamp/set_replacementfont/)(System::SharedPtr\<Text::Font\>) | Sets font used for replacing if user font does not contain required character. |
| [set_RightMargin](../stamp/set_rightmargin/)(double) | Sets right margin of stamp. |
| [set_Rotate](../stamp/set_rotate/)(Rotation) | Sets or gets the rotation of stamp content according [Rotation](../rotation/) values. [Note](../note/). This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns [Rotation.None](../rotation/). |
| [set_RotateAngle](../stamp/set_rotateangle/)(double) | Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [set_Scale](../textstamp/set_scale/)(bool) | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Sets value of the number of starting page. Other pages will be numbered starting from this value. |
| [set_TextAlignment](../textstamp/set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Alignment of the text inside the stamp. |
| [set_TopMargin](../stamp/set_topmargin/)(double) | Sets top margin of stamp. |
| [set_TreatYIndentAsBaseLine](../textstamp/set_treatyindentasbaseline/)(bool) | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [set_Value](../textstamp/set_value/)(System::String) | Sets string value which is used as stamp on the page. |
| [set_VerticalAlignment](../stamp/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets vertical alignment of stamp on page. |
| [set_Width](../textstamp/set_width/)(double) override | Desired width of the stamp on the page. |
| [set_WordWrap](../textstamp/set_wordwrap/)(bool) | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [set_WordWrapMode](../textstamp/set_wordwrapmode/)(Aspose::Pdf::Text::TextFormattingOptions::WordWrapMode) | Sets the word wrap mode for text rendering. |
| [set_XIndent](../stamp/set_xindent/)(double) | Horizontal stamp coordinate, starting from the left. |
| [set_YIndent](../stamp/set_yindent/)(double) | Vertical stamp coordinate, starting from the bottom. |
| [set_Zoom](../stamp/set_zoom/)(double) | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [set_ZoomX](../stamp/set_zoomx/)(double) | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [set_ZoomY](../stamp/set_zoomy/)(double) | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [setStampId](../stamp/setstampid/)(int32_t) | Sets stamp [Id](../id/). |
| [Stamp](../stamp/stamp/)() |  |
| [TextStamp](../textstamp/textstamp/)(System::String) | Initializes a new instance of the [TextStamp](../textstamp/) class. |
| [TextStamp](../textstamp/textstamp/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Initializes a new instance of the [TextStamp](../textstamp/) class. |
| [TextStamp](../textstamp/textstamp/)(System::SharedPtr\<Facades::FormattedText\>) | Initializes a new instance of the [TextStamp](../textstamp/) class with formattedText object. |
## See Also

* Class [TextStamp](../textstamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
