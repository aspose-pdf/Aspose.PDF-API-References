---
title: TextFragment
second_title: Aspose.PDF för .NET API Referens
description: Representerar fragment av pdf-text.
type: docs
weight: 7100
url: /sv/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Representerar fragment av pdf-text.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Initierar ny instans av[`TextFragment`](../textfragment) objekt. |
| [TextFragment](textfragment#constructor_2)(string) | Skapar[`TextFragment`](../textfragment) objekt med singel[`TextSegment`](../textsegment) föremål inuti. Anger textsträng inuti segmentet. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Initierar ny instans av[`TextFragment`](../textfragment) objekt med fördefinierade[`TabStops`](../tabstops) positioner. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Skapar[`TextFragment`](../textfragment) objekt med singel[`TextSegment`](../textsegment) objekt inuti och fördefinierat[`TabStops`](../tabstops) positioner. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Får textposition för text, representerad med[`TextFragment`](../textfragment) object. YIndent av positionsstrukturen representerar baslinjekoordinaten för textfragmentet. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Hämtar eller ställer in styckeslutnoten.(endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Hämtar eller ställer in styckets fotnot.(endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Hämtar formulärobjekt som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Hämtar eller ställer in en horisontell justering av textfragment. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Ställer in fragmentets hyperlänk |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Hämtar sida som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Hämtar eller ställer in textposition för text, representerad med[`TextFragment`](../textfragment) objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Får rektangel av TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Får textersättningsalternativ. Alternativen definierar beteende när fragmenterad text ersätts till mer kort/lång. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Hämtar textsegment för nuvarande[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Hämtar eller sätterString textobjekt som[`TextFragment`](../textfragment) objekt representerar. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Hämtar eller ställer in texttillstånd för texten som[`TextFragment`](../textfragment) objekt representerar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av textfragment. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Hämtar eller ställer in radbrytningsantal för detta stycke (endast för pdf-generering) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Klona fragmentet. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Klona fragmentet med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Blir[`TextSegment`](../textsegment) (s) representerar specificerad del av[`TextFragment`](../textfragment) text. |

### Anmärkningar

Med några få ord,[`TextFragment`](../textfragment) objektet innehåller lista över[`TextSegment`](../textsegment) objekt. I detaljer: Text i pdf-dokument iPdf representeras av två grundläggande objekt:[`TextFragment`](../textfragment) och[`TextSegment`](../textsegment) Skillnaderna mellan dem är mestadels kontextberoende. Låt oss överväga följande scenario. Användaren söker efter texten "hej världen" för att arbeta med den, ändra dess egenskaper, utseende etc. Fysiskt sett är pdf-textens representation mycket komplex. Texten "hej världen" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen slår i grunden fast att[`TextFragment`](../textfragment) object tillhandahåller en enda logisk operation satt över fysisk[`TextSegment`](../textsegment) objektuppsättning som representerar användarens fråga. I textsökningsscenario,[`TextFragment`](../textfragment) är logisk "hej världen" textrepresentation, och[`TextSegment`](../textsegment)objektsamling representerar alla fysiska segment som konstruerar "hej världen" textobjekt. Så,[`TextFragment`](../textfragment) är nära logisk textrepresentation. And[`TextSegment`](../textsegment) är nära fysisk textrepresentation. Uppenbarligen var och en[`TextSegment`](../textsegment) objektet kan ha sitt eget typsnitt, färg, positioneringsegenskaper. [`TextFragment`](../textfragment) ger ett enkelt sätt att ändra text med dess egenskaper: ställ in teckensnitt, ställ in teckenstorlek, ställ in teckensnittsfärg etc. Under tiden[`TextSegment`](../textsegment) objekt är tillgängliga och användare kan arbeta med[`TextSegment`](../textsegment) objekt oberoende. Observera att ändringar av TextFragment-egenskaper kan ändras inre[`Segments`](./segments) samling eftersom TextFragment är ett aggregerat objekt och det kan ordna om interna segment eller slå samman dem till ett enda segment. Om ditt krav är att lämna[`Segments`](./segments)samlingen oförändrad, vänligen ändra inre segment individuellt.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten och dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som kommer att användas för att ändra teckensnitt för dokumenttext
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* namnutrymme [Aspose.Pdf.Text](../../aspose.pdf.text)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
