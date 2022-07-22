---
title: TextFragmentState
second_title: Aspose.PDF för .NET API Referens
description: Representerar ett texttillstånd för ett textfragment.
type: docs
weight: 7130
url: /sv/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Representerar ett texttillstånd för ett textfragment.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Initierar ny instans av[`TextFragmentState`](../textfragmentstate) objekt med specificerat[`TextFragment`](../textfragment) object. Detta[`TextFragmentState`](../textfragmentstate) initiering stöds inte. TextFragmentState är endast tillgänglig med[`TextState`](../textfragment/textstate) egenskap. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Ställer in bakgrundsfärgen för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Hämtar eller ställer in teckenavstånd för texten, representerat av[`TextFragment`](../textfragment) objekt. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Hämtar eller ställer in om text rektangel kantlinje ritad flagga. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Hämtar eller ställer in teckensnitt för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Hämtar eller ställer in teckenstorlek för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Anger teckensnitt för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Hämtar eller ställer in förgrundsfärgen på texten, representerad av[`TextFragment`](../textfragment) objekt |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Hämtar eller ställer in formateringsalternativ. Inställning av alternativen kommer endast att gälla i generatorscenarier. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Hämtar eller ställer in horisontell justering för texten. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Får eller ställer in horisontell skalning av texten, representerad av[`TextFragment`](../textfragment) objekt. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Får eller ställer in textens osynlighet. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Hämtar eller ställer in radavstånd för texten. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Hämtar eller ställer in renderingsläge för texten. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Hämtar eller ställer in rotationsvinkeln i grader. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Ställer överstruken för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Får eller ställer in färgstrykningsoperationer av[`TextFragment`](../textfragment) rendering (linjetext, rektangelkant) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Hämtar eller ställer in subscript av texten, representerad av[`TextFragment`](../textfragment) objekt. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Hämtar eller ställer in upphöjd text av texten, representerad av[`TextFragment`](../textfragment) objekt. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Får tabbstopp för texten. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Får eller sätter understrykning för texten, representerad av[`TextFragment`](../textfragment) objekt |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Hämtar eller ställer in ordavstånd för texten. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Tillämpar inställningar från en annan textState. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Mäter strängen. |

## Fält

| namn | Beskrivning |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Standardvärde för tabulering i mellanslagsbredder för standardteckensnitt. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Du kan placera denna tagg i text för att deklarera tabulering. |

### Anmärkningar

Ger ett sätt att ändra följande egenskaper för texten: teckensnitt ([`Font`](./font) egenskap) teckenstorlek ([`FontSize`](./fontsize) egenskap) teckensnittsstil ([`FontStyle`](./fontstyle) egenskap) förgrundsfärg ([`ForegroundColor`](./foregroundcolor) egenskap) bakgrundsfärg ([`BackgroundColor`](./backgroundcolor) egenskap) Observera att ändring[`TextFragmentState`](../textfragmentstate) egenskaper kan förändras inre[`Segments`](../textfragment/segments) samling eftersom TextFragment är ett aggregerat objekt och det kan ordna om interna segment eller slå samman dem till ett enda segment. Om ditt krav är att lämna[`Segments`](../textfragment/segments) samlingen oförändrad, vänligen ändra inre segment individuellt.

### Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek på texten med[`TextState`](../textstate) objekt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra förgrundsfärgen för den första textförekomsten
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ändra teckenstorlek för den första textförekomsten
absorber.TextFragments[1].TextState.FontSize = 15;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* namnutrymme [Aspose.Pdf.Text](../../aspose.pdf.text)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
