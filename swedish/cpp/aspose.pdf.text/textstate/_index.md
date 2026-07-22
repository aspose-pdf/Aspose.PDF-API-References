---
title: "Aspose::Pdf::Text::TextState-klass"
linktitle: "TextState"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextState-klass. Representerar ett texttillstånd för en text i C++."
type: docs
weight: 5300
url: /sv/cpp/aspose.pdf.text/textstate/
---
## TextState class


Representerar ett texttillstånd för en text.

```cpp
class TextState : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) | Tillämpar inställningar från ett annat textState. |
| virtual [get_BackgroundColor](./get_backgroundcolor/)() | Ställer in bakgrundsfärgen för texten. |
| virtual [get_CharacterSpacing](./get_characterspacing/)() | Hämtar teckenavståndet för texten. |
| virtual [get_CoordinateOrigin](./get_coordinateorigin/)() | Hämtar textens [CoordinateOrigin](../coordinateorigin/). Om [CoordinateOrigin](../coordinateorigin/) är Descender motsvarar textens Y-koordinat teckensnittets lägsta punkt. Om [CoordinateOrigin](../coordinateorigin/) är BaseLine motsvarar textens Y-koordinat teckensnittets baslinje. Standardvärdet är Descender. Om teckensnittets Descent‑värde är för stort kan text renderas högre än andra teckensnitt. I detta fall kan [CoordinateOrigin](../coordinateorigin/) BaseLine väljas för bättre textrendering. |
| virtual [get_Font](./get_font/)() | Hämtar teckensnittet för texten. |
| virtual [get_FontSize](./get_fontsize/)() | Hämtar teckenstorleken för texten. |
| virtual [get_FontStyle](./get_fontstyle/)() | Ställer in teckensnittsstilen för texten. |
| virtual [get_ForegroundColor](./get_foregroundcolor/)() | Hämtar förgrundsfärgen för texten. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Hämtar horisontell justering för texten. |
| virtual [get_HorizontalScaling](./get_horizontalscaling/)() | Hämtar horisontell skalning av texten. |
| virtual [get_Invisible](./get_invisible/)() | Hämtar textens osynlighet. Detta speglar i princip [RenderingMode](../)-tillståndet, förutom vissa speciella fall (som beskärning). |
| virtual [get_LineSpacing](./get_linespacing/)() | Hämtar radavståndet för texten. |
| virtual [get_RenderingMode](./get_renderingmode/)() | Hämtar renderingsläget för texten. |
| virtual [get_StrikeOut](./get_strikeout/)() | Hämtar genomstrykning för texten, representerad av [TextSegment](../textsegment/)-objektet. |
| virtual [get_StrokingColor](./get_strokingcolor/)() | Hämtar förgrundsfärgen för texten. |
| virtual [get_Subscript](./get_subscript/)() | Hämtar nedsänkt text. |
| virtual [get_Superscript](./get_superscript/)() | Hämtar upphöjd text. |
| [get_TabTag](./get_tabtag/)() | Du kan placera den här taggen i texten för att ange tabulering. |
| virtual [get_Underline](./get_underline/)() | Hämtar understrykning för texten, representerad av objektet [TextFragment](../textfragment/). |
| virtual [get_WordSpacing](./get_wordspacing/)() | Hämtar ordavstånd för texten. |
| [MeasureHeight](./measureheight/)(char16_t) | Mäter teckenhöjd. |
| virtual [MeasureString](./measurestring/)(const System::String\&) | Mäter strängen. |
| virtual [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Ställer in bakgrundsfärgen för texten. |
| virtual [set_CharacterSpacing](./set_characterspacing/)(float) | Ställer in teckenavstånd för texten. |
| virtual [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) | Sätter textens [CoordinateOrigin](../coordinateorigin/). Om [CoordinateOrigin](../coordinateorigin/) är Descender motsvarar textens Y-koordinat tecknets lägsta punkt. Om [CoordinateOrigin](../coordinateorigin/) är BaseLine motsvarar textens Y-koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan [CoordinateOrigin](../coordinateorigin/) BaseLine väljas för bättre textrendering. |
| virtual [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Ställer in teckensnitt för texten. |
| virtual [set_FontSize](./set_fontsize/)(float) | Ställer in teckenstorlek för texten. |
| virtual [set_FontStyle](./set_fontstyle/)(FontStyles) | Ställer in teckensnittsstilen för texten. |
| virtual [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) | Ställer in förgrundsfärg för texten. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in horisontell justering för texten. |
| virtual [set_HorizontalScaling](./set_horizontalscaling/)(float) | Ställer in horisontell skalning av texten. |
| virtual [set_Invisible](./set_invisible/)(bool) | Ställer in textens osynlighet. Detta speglar i princip [RenderingMode](../)-tillståndet, förutom i vissa speciella fall (t.ex. beskärning). |
| virtual [set_LineSpacing](./set_linespacing/)(float) | Ställer in radavstånd för texten. |
| virtual [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) | Ställer in renderingsläge för texten. |
| virtual [set_StrikeOut](./set_strikeout/)(bool) | Ställer in genomstrykning för texten, representerad av objektet [TextSegment](../textsegment/). |
| virtual [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) | Ställer in förgrundsfärg för texten. |
| virtual [set_Subscript](./set_subscript/)(bool) | Ställer in nedsänkt text. |
| virtual [set_Superscript](./set_superscript/)(bool) | Ställer in upphöjd text. |
| virtual [set_Underline](./set_underline/)(bool) | Ställer in understrykning för texten, representerad av objektet [TextFragment](../textfragment/). |
| virtual [set_WordSpacing](./set_wordspacing/)(float) | Ställer in ordavstånd för texten. |
| [TextState](./textstate/)() | Skapar texttillståndsobjekt. |
| [TextState](./textstate/)(double) | Skapar texttillståndsobjekt med teckenstorleksspecifikation. |
| [TextState](./textstate/)(System::Drawing::Color) | Skapar texttillståndsobjekt med förgrundsfärgspecifikation. |
| [TextState](./textstate/)(System::Drawing::Color, double) | Skapar texttillståndsobjekt med förgrundsfärg och teckenstorleksspecifikation. |
| [TextState](./textstate/)(const System::String\&) | Skapar texttillståndsobjekt med teckensnittsfamiljsspecifikation. |
| [TextState](./textstate/)(const System::String\&, bool, bool) | Skapar texttillståndsobjekt med teckensnittsfamilj och teckensnittsstilsspecifikation. |
| [TextState](./textstate/)(const System::String\&, double) | Skapar texttillståndsobjekt med teckensnittsfamilj och teckenstorleksspecifikation. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
