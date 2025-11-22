---
title: Aspose::Pdf::Text::TextFragmentState class
linktitle: TextFragmentState
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentState class. Represents a text state of a text fragment in C++.'
type: docs
weight: 4600
url: /cpp/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class


Represents a text state of a text fragment.

```cpp
class TextFragmentState : public Aspose::Pdf::Text::TextState
```

## Methods

| Method | Description |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) override | Applies settings from another textState. |
| [get_BackgroundColor](./get_backgroundcolor/)() override | Sets background color of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_CharacterSpacing](./get_characterspacing/)() override | Gets character spacing of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_CoordinateOrigin](./get_coordinateorigin/)() override | Gets text [CoordinateOrigin](../coordinateorigin/). If [CoordinateOrigin](../coordinateorigin/) is Descender, the text Y coordinate corresponds to the font's lowest point. If [CoordinateOrigin](../coordinateorigin/) is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, [CoordinateOrigin](../coordinateorigin/) BaseLine can be selected for better text rendering. |
| [get_DrawTextRectangleBorder](./get_drawtextrectangleborder/)() const | Gets if text rectangle border drawn flag. |
| [get_Font](./get_font/)() override | Gets font of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_FontSize](./get_fontsize/)() override | Gets font size of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_FontStyle](./get_fontstyle/)() override | Sets font style of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_ForegroundColor](./get_foregroundcolor/)() override | Gets foreground color of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_FormattingOptions](./get_formattingoptions/)() const | Gets formatting options. Setting of the options will be effective in generator scenarios only. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Gets horizontal alignment for the text. |
| [get_HorizontalScaling](./get_horizontalscaling/)() override | Gets horizontal scaling of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_Invisible](./get_invisible/)() override | Gets invisibility of the text. |
| [get_LineSpacing](./get_linespacing/)() override | Gets line spacing of the text. |
| [get_RenderingMode](./get_renderingmode/)() override | Gets rendering mode of the text. |
| [get_Rotation](./get_rotation/)() | Gets rotation angle in degrees. |
| [get_StrikeOut](./get_strikeout/)() override | Gets strikeout for the text, represented by the [TextFragment](../textfragment/) object. |
| [get_StrokingColor](./get_strokingcolor/)() override | Gets color stroking operations of [TextFragment](../textfragment/) rendering (stroke text, rectangle border) |
| [get_Subscript](./get_subscript/)() override | Gets subscript of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_Superscript](./get_superscript/)() override | Gets superscript of the text, represented by the [TextFragment](../textfragment/) object. |
| [get_TabStops](./get_tabstops/)() const | Gets tabstops for the text. |
| [get_Underline](./get_underline/)() override | Gets underline for the text, represented by the [TextFragment](../textfragment/) object. |
| [get_WordSpacing](./get_wordspacing/)() override | Gets word spacing of the text. |
| [IsFitRectangle](./isfitrectangle/)(System::String, System::SharedPtr\<Rectangle\>) | Checks if input string could be placed inside defined rectangle. |
| [MeasureHeight](./measureheight/)(char16_t) | Measures character height. |
| [MeasureString](./measurestring/)(const System::String\&) override | Measures the string. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) override | Sets background color of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_CharacterSpacing](./set_characterspacing/)(float) override | Sets character spacing of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) override | Sets text [CoordinateOrigin](../coordinateorigin/). If [CoordinateOrigin](../coordinateorigin/) is Descender, the text Y coordinate corresponds to the font's lowest point. If [CoordinateOrigin](../coordinateorigin/) is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, [CoordinateOrigin](../coordinateorigin/) BaseLine can be selected for better text rendering. |
| [set_DrawTextRectangleBorder](./set_drawtextrectangleborder/)(bool) | Sets if text rectangle border drawn flag. |
| [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) override | Sets font of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_FontSize](./set_fontsize/)(float) override | Sets font size of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_FontStyle](./set_fontstyle/)(FontStyles) override | Sets font style of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) override | Sets foreground color of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_FormattingOptions](./set_formattingoptions/)(System::SharedPtr\<TextFormattingOptions\>) | Sets formatting options. Setting of the options will be effective in generator scenarios only. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets horizontal alignment for the text. |
| [set_HorizontalScaling](./set_horizontalscaling/)(float) override | Sets horizontal scaling of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_Invisible](./set_invisible/)(bool) override | Sets invisibility of the text. |
| [set_LineSpacing](./set_linespacing/)(float) override | Sets line spacing of the text. |
| [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) override | Sets rendering mode of the text. |
| [set_Rotation](./set_rotation/)(double) | Sets rotation angle in degrees. |
| [set_StrikeOut](./set_strikeout/)(bool) override | Sets strikeout for the text, represented by the [TextFragment](../textfragment/) object. |
| [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) override | Sets color stroking operations of [TextFragment](../textfragment/) rendering (stroke text, rectangle border) |
| [set_Subscript](./set_subscript/)(bool) override | Sets subscript of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_Superscript](./set_superscript/)(bool) override | Sets superscript of the text, represented by the [TextFragment](../textfragment/) object. |
| [set_Underline](./set_underline/)(bool) override | Sets underline for the text, represented by the [TextFragment](../textfragment/) object. |
| [set_WordSpacing](./set_wordspacing/)(float) override | Sets word spacing of the text. |
| [TextFragmentState](./textfragmentstate/)(System::SharedPtr\<TextFragment\>) | Initializes new instance of the [TextFragmentState](./) object with specified [TextFragment](../textfragment/) object. This [TextFragmentState](./) initialization is not supported. [TextFragmentState](./) is only available with [TextFragment::TextState](../) property. |
## Remarks


Provides a way to change following properties of the text: font ([TextFragmentState::Font](../) property) font size ([TextFragmentState::FontSize](../) property) font style ([TextFragmentState::FontStyle](../) property) foreground color ([TextFragmentState::ForegroundColor](../) property) background color ([TextFragmentState::BackgroundColor](../) property)

[Note](../../aspose.pdf/note/) that changing [TextFragmentState](./) properties may change inner [TextFragment::Segments](../) collection because [TextFragment](../textfragment/) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [TextFragment::Segments](../) collection unchanged, please change inner segments individually. 


## See Also

* Class [TextState](../textstate/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
