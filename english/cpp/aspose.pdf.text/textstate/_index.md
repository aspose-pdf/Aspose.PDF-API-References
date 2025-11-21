---
title: Aspose::Pdf::Text::TextState class
linktitle: TextState
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextState class. Represents a text state of a text in C++.'
type: docs
weight: 5300
url: /cpp/aspose.pdf.text/textstate/
---
## TextState class


Represents a text state of a text.

```cpp
class TextState : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) | Applies settings from another textState. |
| virtual [get_BackgroundColor](./get_backgroundcolor/)() | Sets background color of the text. |
| virtual [get_CharacterSpacing](./get_characterspacing/)() | Gets character spacing of the text. |
| virtual [get_CoordinateOrigin](./get_coordinateorigin/)() | Gets text [CoordinateOrigin](../coordinateorigin/). If [CoordinateOrigin](../coordinateorigin/) is Descender, the text Y coordinate corresponds to the font's lowest point. If [CoordinateOrigin](../coordinateorigin/) is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, [CoordinateOrigin](../coordinateorigin/) BaseLine can be selected for better text rendering. |
| virtual [get_Font](./get_font/)() | Gets font of the text. |
| virtual [get_FontSize](./get_fontsize/)() | Gets font size of the text. |
| virtual [get_FontStyle](./get_fontstyle/)() | Sets font style of the text. |
| virtual [get_ForegroundColor](./get_foregroundcolor/)() | Gets foreground color of the text. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Gets horizontal alignment for the text. |
| virtual [get_HorizontalScaling](./get_horizontalscaling/)() | Gets horizontal scaling of the text. |
| virtual [get_Invisible](./get_invisible/)() | Gets the invisibility of text. This basically reflects the [RenderingMode](../) state, except for some special cases (like clipping). |
| virtual [get_LineSpacing](./get_linespacing/)() | Gets line spacing of the text. |
| virtual [get_RenderingMode](./get_renderingmode/)() | Gets rendering mode of text. |
| virtual [get_StrikeOut](./get_strikeout/)() | Gets strikeout for the text, represented by the [TextSegment](../textsegment/) object. |
| virtual [get_StrokingColor](./get_strokingcolor/)() | Gets foreground color of the text. |
| virtual [get_Subscript](./get_subscript/)() | Gets subscript of the text. |
| virtual [get_Superscript](./get_superscript/)() | Gets superscript of the text. |
| [get_TabTag](./get_tabtag/)() | You can place this tag in text to declare tabulation. |
| virtual [get_Underline](./get_underline/)() | Gets underline for the text, represented by the [TextFragment](../textfragment/) object. |
| virtual [get_WordSpacing](./get_wordspacing/)() | Gets word spacing of the text. |
| [MeasureHeight](./measureheight/)(char16_t) | Measures character height. |
| virtual [MeasureString](./measurestring/)(const System::String\&) | Measures the string. |
| virtual [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets background color of the text. |
| virtual [set_CharacterSpacing](./set_characterspacing/)(float) | Sets character spacing of the text. |
| virtual [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) | Sets text [CoordinateOrigin](../coordinateorigin/). If [CoordinateOrigin](../coordinateorigin/) is Descender, the text Y coordinate corresponds to the font's lowest point. If [CoordinateOrigin](../coordinateorigin/) is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, [CoordinateOrigin](../coordinateorigin/) BaseLine can be selected for better text rendering. |
| virtual [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Sets font of the text. |
| virtual [set_FontSize](./set_fontsize/)(float) | Sets font size of the text. |
| virtual [set_FontStyle](./set_fontstyle/)(FontStyles) | Sets font style of the text. |
| virtual [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) | Sets foreground color of the text. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets horizontal alignment for the text. |
| virtual [set_HorizontalScaling](./set_horizontalscaling/)(float) | Sets horizontal scaling of the text. |
| virtual [set_Invisible](./set_invisible/)(bool) | Sets the invisibility of text. This basically reflects the [RenderingMode](../) state, except for some special cases (like clipping). |
| virtual [set_LineSpacing](./set_linespacing/)(float) | Sets line spacing of the text. |
| virtual [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) | Sets rendering mode of text. |
| virtual [set_StrikeOut](./set_strikeout/)(bool) | Sets strikeout for the text, represented by the [TextSegment](../textsegment/) object. |
| virtual [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) | Sets foreground color of the text. |
| virtual [set_Subscript](./set_subscript/)(bool) | Sets subscript of the text. |
| virtual [set_Superscript](./set_superscript/)(bool) | Sets superscript of the text. |
| virtual [set_Underline](./set_underline/)(bool) | Sets underline for the text, represented by the [TextFragment](../textfragment/) object. |
| virtual [set_WordSpacing](./set_wordspacing/)(float) | Sets word spacing of the text. |
| [TextState](./textstate/)() | Creates text state object. |
| [TextState](./textstate/)(double) | Creates text state object with font size specification. |
| [TextState](./textstate/)(System::Drawing::Color) | Creates text state object with foreground color specification. |
| [TextState](./textstate/)(System::Drawing::Color, double) | Creates text state object with foreground color and font size specification. |
| [TextState](./textstate/)(System::String) | Creates text state object with font family specification. |
| [TextState](./textstate/)(System::String, bool, bool) | Creates text state object with font family and font style specification. |
| [TextState](./textstate/)(System::String, double) | Creates text state object with font family and font size specification. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
