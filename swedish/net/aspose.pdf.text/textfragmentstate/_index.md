---
title: "Klass TextFragmentState"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextFragmentState class. Representerar ett texttillstånd för ett textfragment"
type: docs
weight: 11150
url: /sv/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Representerar ett texttillstånd för ett textfragment.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Initierar en ny instans av `TextFragmentState`-objektet med angivet [`TextFragment`](../textfragment/) objekt. Denna `TextFragmentState`-initialisering stöds inte. TextFragmentState är endast tillgänglig med [`TextState`](../textfragment/textstate/) egenskapen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Ställer in bakgrundsfärgen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Hämtar eller anger teckenavståndet för texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat teckensnittets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat teckensnittets baslinje. Standardvärdet är Descender. Om teckensnittets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Hämtar eller anger flaggan för om textrutans kant ska ritas. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Hämtar eller anger teckensnittet för texten, representerat av [`TextFragment`](../textfragment/) objektet |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Hämtar eller anger teckensnittsstorleken för texten, representerat av [`TextFragment`](../textfragment/) objektet |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Ställer in teckensnittsstilen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Hämtar eller anger förgrundsfärgen för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Hämtar eller anger formateringsalternativ. Inställning av alternativen kommer endast att vara effektiv i generator-scenarier. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering för texten. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Hämtar eller anger horisontell skalning av texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Hämtar eller anger osynlighet för texten. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Hämtar eller anger radavståndet för texten. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Hämtar eller anger renderingsläge för texten. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Hämtar eller anger rotationsvinkeln i grader. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Hämtar eller anger genomstrykning för texten, representerad av [`TextFragment`](../textfragment/) objektet |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Hämtar eller anger färg för streckningsoperationer i [`TextFragment`](../textfragment/) rendering (streckad text, rektangelkant) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Hämtar eller anger nedsänkt text för texten, representerad av [`TextFragment`](../textfragment/) objektet. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Hämtar eller anger upphöjd text för texten, representerad av objektet [`TextFragment`](../textfragment/). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Hämtar tabbstopp för texten. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Du kan placera denna tagg i texten för att ange tabulering. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Hämtar eller anger understrykning för texten, representerad av objektet [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Hämtar eller anger ordavståndet för texten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Tillämpar inställningar från ett annat textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Kontrollerar om inmatningssträngen kan placeras inom en definierad rektangel. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mäter teckenhöjd. (2 metoder) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mäter strängen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardvärde för tabulering i bredden på mellanslagstecknet för standardteckensnittet. |

## Anmärkningar

Tillhandahåller ett sätt att ändra följande egenskaper för texten: font ([`Font`](./font/) egenskap) teckenstorlek ([`FontSize`](./fontsize/) egenskap) teckensnittsstil ([`FontStyle`](./fontstyle/) egenskap) förgrundsfärg ([`ForegroundColor`](./foregroundcolor/) egenskap) bakgrundsfärg ([`BackgroundColor`](./backgroundcolor/) egenskap) Observera att ändring av `TextFragmentState`-egenskaper kan ändra den inre [`Segments`](../textfragment/segments/) samlingen eftersom TextFragment är ett aggregatobjekt och kan omarrangera interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att låta [`Segments`](../textfragment/segments/) samlingen förbli oförändrad, ändra de inre segmenten individuellt.

## Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med objektet [`TextState`](../textstate/).

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra förgrundsfärg för den första textförekomsten
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ändra teckenstorlek för den första textförekomsten
absorber.TextFragments[1].TextState.FontSize = 15;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


