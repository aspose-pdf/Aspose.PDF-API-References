---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextState klass. Representerar ett texttillstånd av en text
type: docs
weight: 11070
url: /sv/net/aspose.pdf.text/textstate/
---
## TextState klass

Representerar ett texttillstånd av en text

```csharp
public class TextState
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextState](textstate/#constructor)() | Skapar ett texttillståndsobjekt. |
| [TextState](textstate/#constructor_2)(Color) | Skapar ett texttillståndsobjekt med specifikation av förgrundsfärg. |
| [TextState](textstate/#constructor_1)(double) | Skapar ett texttillståndsobjekt med specifikation av teckenstorlek. |
| [TextState](textstate/#constructor_4)(string) | Skapar ett texttillståndsobjekt med specifikation av typsnittsfamilj. |
| [TextState](textstate/#constructor_3)(Color, double) | Skapar ett texttillståndsobjekt med specifikation av förgrundsfärg och teckenstorlek. |
| [TextState](textstate/#constructor_6)(string, double) | Skapar ett texttillståndsobjekt med specifikation av typsnittsfamilj och teckenstorlek. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Skapar ett texttillståndsobjekt med specifikation av typsnittsfamilj och typsnittsstil. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Ställer in bakgrundsfärgen för texten. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Hämtar eller ställer in teckenavståndet för texten. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Hämtar eller ställer in textens CoordinateOrigin. Om CoordinateOrigin är Descender, motsvarar textens Y-koordinat typsnittets lägsta punkt. Om CoordinateOrigin är BaseLine, motsvarar textens Y-koordinat typsnittets baslinje. Standardvärdet är Descender. Om typsnittets Descent-värde är för stort kan texten renderas högre än andra typsnitt. I detta fall kan CoordinateOrigin BaseLine väljas för bättre textåtergivning. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Hämtar eller ställer in typsnittet för texten. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Hämtar eller ställer in teckenstorleken för texten. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Ställer in typsnittsstilen för texten. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Hämtar eller ställer in förgrundsfärgen för texten. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Hämtar eller ställer in horisontell justering för texten. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Hämtar eller ställer in horisontell skalning av texten. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Hämtar eller ställer in osynligheten av text. Detta återspeglar i grunden [`RenderingMode`](./renderingmode/) tillståndet, förutom i vissa speciella fall (som klippning). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Hämtar eller ställer in radavståndet för texten. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Hämtar eller ställer in återgivningsläget för text. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Hämtar eller ställer in genomstrykning för texten, representerad av [`TextSegment`](../textsegment/) objektet |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Hämtar eller ställer in förgrundsfärgen för texten. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Hämtar eller ställer in subscript för texten. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Hämtar eller ställer in superscript för texten. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Hämtar eller ställer in understrykning för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Hämtar eller ställer in ordavståndet för texten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Tillämpa inställningar från ett annat textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mäta teckenhöjd. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mäta strängen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardvärde för tabulering i bredden av mellanslagstecknet för standardtypsnittet. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Du kan placera denna tagg i texten för att deklarera tabulering. |

### Se Även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)