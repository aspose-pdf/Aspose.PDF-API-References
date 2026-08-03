---
title: "Klass TextFragment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextFragment-klass. Representerar ett fragment av Pdf-text"
type: docs
weight: 11120
url: /sv/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Representerar ett fragment av PDF-text.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Initierar en ny instans av `TextFragment`-objektet. |
| [TextFragment](textfragment/#constructor_2)(string) | Skapar `TextFragment`-objekt med ett enda [`TextSegment`](../textsegment/)-objekt inuti. Anger textsträngen i segmentet. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Initierar en ny instans av `TextFragment`-objektet med fördefinierade [`TabStops`](../tabstops/)-positioner. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Skapar `TextFragment`-objekt med ett enda [`TextSegment`](../textsegment/)-objekt inuti och fördefinierade [`TabStops`](../tabstops/)-positioner. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med `TextFragment`-objekt. YIndent i Position-strukturen representerar baslinjekoordinationen för textfragmentet. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Hämtar eller anger paragrafens slutnot.(endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Hämtar eller anger paragrafens fotnot.(endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Hämtar formulärobjektet som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av textfragmentet. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Anger fragmentets hyperlänk |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Hämtar sidan som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Hämtar eller anger textposition för text, representerad med `TextFragment`-objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Hämtar rektangeln för TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare/längre text. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Hämtar textsegment för aktuell `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Hämtar eller anger String‑textobjektet som `TextFragment`‑objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Hämtar eller anger texttillstånd för den text som `TextFragment`‑objektet representerar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering av textfragmentet. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Hämtar eller anger antal radbrytningar för detta stycke (endast för PDF‑generering). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Klona fragmentet. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Klona fragmentet med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Hämtar [`TextSegment`](../textsegment/)-(er) som representerar den angivna delen av `TextFragment`‑texten. |

## Anmärkningar

Med några ord innehåller `TextFragment`‑objektet en lista med [`TextSegment`](../textsegment/)-objekt. I detalj: Texten i en pdf‑dokument i Pdf representeras av två grundläggande objekt: `TextFragment` och [`TextSegment`](../textsegment/). Skillnaderna mellan dem är mest kontextberoende. Låt oss betrakta följande scenario. Användaren söker efter texten \"hello world\" för att arbeta med den, ändra dess egenskaper, visa den etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Den fysiska representationen av pdf‑text är mycket komplex. Texten \"hello world\" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf‑textmodellen fastställer i princip att `TextFragment`‑objektet tillhandahåller en logisk operation över en uppsättning fysiska [`TextSegment`](../textsegment/)-objekt som representerar användarens fråga. I ett textsök‑scenario är `TextFragment` en logisk representation av texten \"hello world\", och samlingen av [`TextSegment`](../textsegment/)-objekt representerar alla fysiska segment som bygger upp \"hello world\"‑textobjektet. Således ligger `TextFragment` nära den logiska textrepresentationen, medan [`TextSegment`](../textsegment/) ligger nära den fysiska textrepresentationen. Uppenbarligen kan varje [`TextSegment`](../textsegment/)-objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. `TextFragment` erbjuder ett enkelt sätt att ändra texten med dess egenskaper: sätt teckensnitt, teckenstorlek, teckensnittsfärg osv. Samtidigt är [`TextSegment`](../textsegment/)-objekt tillgängliga och användare kan arbeta med dem oberoende. Observera att ändring av TextFragment‑egenskaper kan förändra den inre [`Segments`](./segments/)-samlingen eftersom `TextFragment` är ett aggregatobjekt och kan omordna interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att låta [`Segments`](./segments/)-samlingen förbli oförändrad, ändra då de inre segmenten individuellt.

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten samt dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


