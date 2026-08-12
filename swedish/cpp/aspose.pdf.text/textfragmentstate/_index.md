---
title: "Aspose::Pdf::Text::TextFragmentState-klass"
linktitle: "TextFragmentState"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragmentState-klass. Representerar ett texttillstånd för ett textfragment i C++."
type: docs
weight: 4600
url: /sv/cpp/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class


Representerar ett texttillstånd för ett textfragment.

```cpp
class TextFragmentState : public Aspose::Pdf::Text::TextState
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) override | Tillämpar inställningar från ett annat textState. |
| [get_BackgroundColor](./get_backgroundcolor/)() override | Ställer in bakgrundsfärgen för texten, representerad av objektet [TextFragment](../textfragment/). |
| [get_CharacterSpacing](./get_characterspacing/)() override | Hämtar teckenavståndet för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_CoordinateOrigin](./get_coordinateorigin/)() override | Hämtar textens [CoordinateOrigin](../coordinateorigin/). Om [CoordinateOrigin](../coordinateorigin/) är Descender motsvarar textens Y-koordinat teckensnittets lägsta punkt. Om [CoordinateOrigin](../coordinateorigin/) är BaseLine motsvarar textens Y-koordinat teckensnittets baslinje. Standardvärdet är Descender. Om teckensnittets Descent‑värde är för stort kan text renderas högre än andra teckensnitt. I detta fall kan [CoordinateOrigin](../coordinateorigin/) BaseLine väljas för bättre textrendering. |
| [get_DrawTextRectangleBorder](./get_drawtextrectangleborder/)() const | Hämtar flaggan för om textrutans kant ritas. |
| [get_Font](./get_font/)() override | Hämtar teckensnittet för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_FontSize](./get_fontsize/)() override | Hämtar teckensnittsstorleken för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_FontStyle](./get_fontstyle/)() override | Ställer in teckensnittsstilen för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_ForegroundColor](./get_foregroundcolor/)() override | Hämtar förgrundsfärgen för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_FormattingOptions](./get_formattingoptions/)() const | Hämtar formateringsalternativ. Inställning av alternativen kommer endast att vara effektiv i generator-scenarier. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Hämtar horisontell justering för texten. |
| [get_HorizontalScaling](./get_horizontalscaling/)() override | Hämtar horisontell skalning av texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_Invisible](./get_invisible/)() override | Hämtar osynlighet för texten. |
| [get_LineSpacing](./get_linespacing/)() override | Hämtar radavståndet för texten. |
| [get_RenderingMode](./get_renderingmode/)() override | Hämtar renderingsläget för texten. |
| [get_Rotation](./get_rotation/)() | Hämtar rotationsvinkeln i grader. |
| [get_StrikeOut](./get_strikeout/)() override | Hämtar genomstrykning för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_StrokingColor](./get_strokingcolor/)() override | Hämtar färgstrokoperationer för rendering av [TextFragment](../textfragment/) (strokning av text, rektangelkant) |
| [get_Subscript](./get_subscript/)() override | Hämtar nedsänkt text för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_Superscript](./get_superscript/)() override | Hämtar upphöjd text för texten, representerat av objektet [TextFragment](../textfragment/). |
| [get_TabStops](./get_tabstops/)() const | Hämtar tabbstopp för texten. |
| [get_Underline](./get_underline/)() override | Hämtar understrykning för texten, representerad av objektet [TextFragment](../textfragment/). |
| [get_WordSpacing](./get_wordspacing/)() override | Hämtar ordavstånd för texten. |
| [IsFitRectangle](./isfitrectangle/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Kontrollerar om inmatningssträngen kan placeras inom den definierade rektangeln. |
| [MeasureHeight](./measureheight/)(char16_t) | Mäter teckenhöjd. |
| [MeasureString](./measurestring/)(const System::String\&) override | Mäter strängen. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) override | Ställer in bakgrundsfärgen för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_CharacterSpacing](./set_characterspacing/)(float) override | Ställer in teckenavståndet för texten, representerat av objektet [TextFragment](../textfragment/). |
| [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) override | Sätter textens [CoordinateOrigin](../coordinateorigin/). Om [CoordinateOrigin](../coordinateorigin/) är Descender motsvarar textens Y-koordinat tecknets lägsta punkt. Om [CoordinateOrigin](../coordinateorigin/) är BaseLine motsvarar textens Y-koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan [CoordinateOrigin](../coordinateorigin/) BaseLine väljas för bättre textrendering. |
| [set_DrawTextRectangleBorder](./set_drawtextrectangleborder/)(bool) | Ställer in flaggan för om textrutans kant ska ritas. |
| [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) override | Ställer in teckensnittet för texten, representerat av objektet [TextFragment](../textfragment/). |
| [set_FontSize](./set_fontsize/)(float) override | Ställer in teckenstorlek för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_FontStyle](./set_fontstyle/)(FontStyles) override | Ställer in teckensnittsstilen för texten, representerat av objektet [TextFragment](../textfragment/). |
| [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) override | Ställer in förgrundsfärg för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Ställer in formateringsalternativ. Inställning av alternativen kommer endast att vara effektiv i generator-scenarier. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Ställer in horisontell justering för texten. |
| [set_HorizontalScaling](./set_horizontalscaling/)(float) override | Ställer in horisontell skalning av texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_Invisible](./set_invisible/)(bool) override | Ställer in osynlighet för texten. |
| [set_LineSpacing](./set_linespacing/)(float) override | Ställer in radavstånd för texten. |
| [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) override | Ställer in renderingsläge för texten. |
| [set_Rotation](./set_rotation/)(double) | Ställer in rotationsvinkeln i grader. |
| [set_StrikeOut](./set_strikeout/)(bool) override | Ställer in genomstrykning för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) override | Ställer in färgstrokoperationer för rendering av [TextFragment](../textfragment/) (strokning av text, rektangelram). |
| [set_Subscript](./set_subscript/)(bool) override | Ställer in nedsänkt text för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_Superscript](./set_superscript/)(bool) override | Ställer in upphöjd text för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_Underline](./set_underline/)(bool) override | Ställer in understrykning för texten, representerad av objektet [TextFragment](../textfragment/). |
| [set_WordSpacing](./set_wordspacing/)(float) override | Ställer in ordavstånd för texten. |
| [TextFragmentState](./textfragmentstate/)(const System::SharedPtr\<TextFragment\>\&) | Initierar en ny instans av objektet [TextFragmentState](./) med angivet [TextFragment](../textfragment/)-objekt. Denna initiering av [TextFragmentState](./) stöds inte. [TextFragmentState](./) är endast tillgänglig via egenskapen [TextFragment::TextState](../). |
## Anmärkningar


Tillhandahåller ett sätt att ändra följande egenskaper för texten: teckensnitt ([TextFragmentState::Font](../) egenskap) teckenstorlek ([TextFragmentState::FontSize](../) egenskap) teckensnittsstil ([TextFragmentState::FontStyle](../) egenskap) förgrundsfärg ([TextFragmentState::ForegroundColor](../) egenskap) bakgrundsfärg ([TextFragmentState::BackgroundColor](../) egenskap).

[Note](../../aspose.pdf/note/) that changing [TextFragmentState](./) properties may change inner [TextFragment::Segments](../) collection because [TextFragment](../textfragment/) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [TextFragment::Segments](../) collection unchanged, please change inner segments individually. 


## Se även

* Class [TextState](../textstate/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
