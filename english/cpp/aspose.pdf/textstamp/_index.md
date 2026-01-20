---
title: Aspose::Pdf::TextStamp class
linktitle: TextStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TextStamp class. Represents textual stamp in C++.'
type: docs
weight: 18400
url: /cpp/aspose.pdf/textstamp/
---
## TextStamp class


Represents textual stamp.

```cpp
class TextStamp : public Aspose::Pdf::Stamp
```

## Enums

| Enum | Description |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Action to perform if font does not contain required character. |
## Methods

| Method | Description |
| --- | --- |
| [get_AutoAdjustFontSizePrecision](./get_autoadjustfontsizeprecision/)() const | Automatically adjust font size precision. Default value: 0.1;. |
| [get_AutoAdjustFontSizeToFitStampRectangle](./get_autoadjustfontsizetofitstamprectangle/)() const | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: [Width](../) and [Height](../). Default width and height are derived from the page rectangle. |
| [get_Draw](./get_draw/)() const | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [get_FontSize](./get_fontsize/)() | Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.) |
| [get_Height](./get_height/)() override | Desired height of the stamp on the page. |
| [get_Justify](./get_justify/)() | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [get_MaxRowWidth](./get_maxrowwidth/)() const | Max row height for WordWrap option. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [get_ReplacementFont](./get_replacementfont/)() const | Gets font used for replacing if user font does not contain required character. |
| [get_Scale](./get_scale/)() const | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [get_TextAlignment](./get_textalignment/)() const | Alignment of the text inside the stamp. |
| [get_TextState](./get_textstate/)() const | Gets text properties of the stamp. See **TextState** for details. |
| [get_TreatYIndentAsBaseLine](./get_treatyindentasbaseline/)() const | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [get_Value](./get_value/)() | Gets string value which is used as stamp on the page. |
| [get_Width](./get_width/)() override | Desired width of the stamp on the page. |
| [get_WordWrap](./get_wordwrap/)() const | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [get_WordWrapMode](./get_wordwrapmode/)() const | Gets the word wrap mode for text rendering. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Adds textual stamp on the page. |
| [set_AutoAdjustFontSizePrecision](./set_autoadjustfontsizeprecision/)(float) | Automatically adjust font size precision. Default value: 0.1;. |
| [set_AutoAdjustFontSizeToFitStampRectangle](./set_autoadjustfontsizetofitstamprectangle/)(bool) | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: [Width](../) and [Height](../). Default width and height are derived from the page rectangle. |
| [set_Draw](./set_draw/)(bool) | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [set_Height](./set_height/)(double) override | Desired height of the stamp on the page. |
| [set_Justify](./set_justify/)(bool) | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [set_MaxRowWidth](./set_maxrowwidth/)(double) | Max row height for WordWrap option. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextStamp::NoCharacterAction) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [set_ReplacementFont](./set_replacementfont/)(System::SharedPtr\<Text::Font\>) | Sets font used for replacing if user font does not contain required character. |
| [set_Scale](./set_scale/)(bool) | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Alignment of the text inside the stamp. |
| [set_TreatYIndentAsBaseLine](./set_treatyindentasbaseline/)(bool) | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [set_Value](./set_value/)(System::String) | Sets string value which is used as stamp on the page. |
| [set_Width](./set_width/)(double) override | Desired width of the stamp on the page. |
| [set_WordWrap](./set_wordwrap/)(bool) | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [set_WordWrapMode](./set_wordwrapmode/)(Aspose::Pdf::Text::TextFormattingOptions::WordWrapMode) | Sets the word wrap mode for text rendering. |
| [TextStamp](./textstamp/)(System::String) | Initializes a new instance of the [TextStamp](./) class. |
| [TextStamp](./textstamp/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Initializes a new instance of the [TextStamp](./) class. |
| [TextStamp](./textstamp/)(System::SharedPtr\<Facades::FormattedText\>) | Initializes a new instance of the [TextStamp](./) class with formattedText object. |
## See Also

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
