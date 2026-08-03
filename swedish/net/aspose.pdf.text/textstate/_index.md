---
title: "Klassen TextState"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextState‑klass. Representerar ett texttillstånd för en text"
type: docs
weight: 11260
url: /sv/net/aspose.pdf.text/textstate/
---
## TextState class

Representerar ett texttillstånd för en text.

```csharp
public class TextState
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextState](textstate/#constructor)() | Skapar ett texttillståndsobjekt. |
| [TextState](textstate/#constructor_2)(Color) | Skapar ett texttillståndsobjekt med specifikation av förgrundsfärg. |
| [TextState](textstate/#constructor_1)(double) | Skapar ett texttillståndsobjekt med specifikation av teckenstorlek. |
| [TextState](textstate/#constructor_4)(string) | Skapar ett texttillståndsobjekt med specifikation av teckensnittsfamilj. |
| [TextState](textstate/#constructor_3)(Color, double) | Skapar ett texttillståndsobjekt med specifikation av förgrundsfärg och teckenstorlek. |
| [TextState](textstate/#constructor_6)(string, double) | Skapar ett texttillståndsobjekt med specifikation av teckensnittsfamilj och teckenstorlek. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Skapar texttillståndsobjekt med specifikation för teckensnittsfamilj och teckensnittsstil. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Ställer in bakgrundsfärgen för texten. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Hämtar eller anger teckenavståndet för texten. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat teckensnittets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat teckensnittets baslinje. Standardvärdet är Descender. Om teckensnittets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Hämtar eller anger teckensnittet för texten. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Hämtar eller anger teckensnittsstorleken för texten. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Anger teckensnittsstilen för texten. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Hämtar eller anger förgrundsfärgen för texten. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering för texten. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Hämtar eller anger horisontell skalning av texten. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Hämtar eller anger textens osynlighet. Detta speglar i princip [`RenderingMode`](./renderingmode/)‑tillståndet, förutom i vissa speciella fall (t.ex. beskärning). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Hämtar eller anger radavståndet för texten. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Hämtar eller anger renderingsläge för texten. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Hämtar eller anger genomstrykning för texten, representerad av objektet [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Hämtar eller anger förgrundsfärgen för texten. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Hämtar eller anger nedsänkt text. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Hämtar eller anger upphöjd text. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Du kan placera denna tagg i texten för att ange tabulering. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Hämtar eller anger understrykning för texten, representerad av objektet [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Hämtar eller anger ordavståndet för texten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Tillämpar inställningar från ett annat textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mäter teckenhöjd. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mäter strängen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardvärde för tabulering i bredden på mellanslagstecknet för standardteckensnittet. |

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


