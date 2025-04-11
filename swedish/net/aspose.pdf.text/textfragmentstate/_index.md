---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState klass. Representerar ett texttillstånd för ett textfragment
type: docs
weight: 10970
url: /sv/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState klass

Representerar ett texttillstånd för ett textfragment.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Initierar en ny instans av `TextFragmentState`-objektet med angivet [`TextFragment`](../textfragment/) objekt. Denna `TextFragmentState`-initiering stöds inte. TextFragmentState är endast tillgänglig med [`TextState`](../textfragment/textstate/) egenskap. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Sätter bakgrundsfärgen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Hämtar eller sätter teckenavståndet för texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Hämtar eller sätter textens CoordinateOrigin. Om CoordinateOrigin är Descender, motsvarar textens Y-koordinat fontens lägsta punkt. Om CoordinateOrigin är BaseLine, motsvarar textens Y-koordinat fontens baslinje. Standardvärdet är Descender. Om fontens Descent-värde är för stort kan texten renderas högre än andra fonter. I detta fall kan CoordinateOrigin BaseLine väljas för bättre textåtergivning. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Hämtar eller sätter om textrektangelns kantlinje är ritad. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Hämtar eller sätter fonten för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Hämtar eller sätter teckenstorleken för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Sätter fontstilen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Hämtar eller sätter förgrundsfärgen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Hämtar eller sätter formateringsalternativ. Inställning av alternativen kommer att vara effektiv i generator-scenarier endast. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Hämtar eller sätter horisontell justering för texten. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Hämtar eller sätter horisontell skalning av texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Hämtar eller sätter osynligheten för texten. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Hämtar eller sätter radavståndet för texten. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Hämtar eller sätter återgivningsläget för texten. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Hämtar eller sätter rotationsvinkeln i grader. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Hämtar eller sätter genomstrykning för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Hämtar eller sätter färg för strykoperationer av [`TextFragment`](../textfragment/) rendering (stryktext, rektangelns kantlinje) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Hämtar eller sätter nedsänkt text för texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Hämtar eller sätter upphöjd text för texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Hämtar tabstoppar för texten. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Hämtar eller sätter understrykning för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Hämtar eller sätter ordavståndet för texten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Tillämpa inställningar från en annan textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Kontrollerar om inmatad sträng kan placeras inuti definierad rektangel. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mäta teckenhöjd. (2 metoder) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mäta strängen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardvärde för tabulering i bredden av mellanslagstecknet för standardfonten. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Du kan placera denna tagg i texten för att deklarera tabulering. |

## Kommentarer

Ger ett sätt att ändra följande egenskaper för texten: font ([`Font`](./font/) egenskap) teckenstorlek ([`FontSize`](./fontsize/) egenskap) fontstil ([`FontStyle`](./fontstyle/) egenskap) förgrundsfärg ([`ForegroundColor`](./foregroundcolor/) egenskap) bakgrundsfärg ([`BackgroundColor`](./backgroundcolor/) egenskap) Observera att ändring av `TextFragmentState`-egenskaper kan ändra den inre [`Segments`](../textfragment/segments/) samlingen eftersom TextFragment är ett aggregatobjekt och det kan omorganisera interna segment eller slå samman dem till ett enda segment. Om ditt krav är att lämna den inre [`Segments`](../textfragment/segments/) samlingen oförändrad, vänligen ändra de inre segmenten individuellt.

## Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med [`TextState`](../textstate/) objekt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [TextFragmentAbsorber](../textfragmentabsorber/)
* klass [Document](../../aspose.pdf/document/)
* klass [TextState](../textstate/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)