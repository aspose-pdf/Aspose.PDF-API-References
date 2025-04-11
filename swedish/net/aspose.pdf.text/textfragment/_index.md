---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment klass. Representerar fragment av Pdf-text
type: docs
weight: 10940
url: /sv/net/aspose.pdf.text/textfragment/
---
## TextFragment klass

Representerar fragment av Pdf-text.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Initierar en ny instans av `TextFragment`-objektet. |
| [TextFragment](textfragment/#constructor_2)(string) | Skapar `TextFragment`-objekt med ett enda [`TextSegment`](../textsegment/) objekt inuti. Anger textsträng inuti segmentet. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Initierar en ny instans av `TextFragment`-objektet med fördefinierade [`TabStops`](../tabstops/) positioner. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Skapar `TextFragment`-objekt med ett enda [`TextSegment`](../textsegment/) objekt inuti och fördefinierade [`TabStops`](../tabstops/) positioner. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med `TextFragment`-objekt. YIndent av Position-strukturen representerar baslinjekoordinaten för textfragmentet. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Hämtar eller ställer in styckets slutnot. (endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Hämtar eller ställer in styckets fotnot. (endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Hämtar formulärobjektet som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av textfragmentet. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Ställer in fragmentets hyperlänk |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om stycket är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Hämtar sidan som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Hämtar eller ställer in textpositionen för text, representerad med `TextFragment`-objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Hämtar rektangeln för TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Hämtar alternativ för textbyte. Alternativen definierar beteende när fragmenttexten ersätts med kortare/längre. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Hämtar textsegment för det aktuella `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Hämtar eller ställer in strängtextobjektet som `TextFragment`-objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Hämtar eller ställer in alternativ för textredigering. Alternativen definierar speciellt beteende när begärd symbol inte kan skrivas med teckensnitt. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Hämtar eller ställer in textstatus för texten som `TextFragment`-objektet representerar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av textfragmentet. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Hämtar eller ställer in antalet omslag för detta stycke (endast för pdf-generering) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Klonar fragmentet. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Klonar fragmentet med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Hämtar [`TextSegment`](../textsegment/)(s) som representerar angiven del av `TextFragment`-texten. |

## Kommentarer

Med några få ord, `TextFragment`-objektet innehåller en lista av [`TextSegment`](../textsegment/) objekt. I detalj: Texten i pdf-dokumentet i Pdf representeras av två grundläggande objekt: `TextFragment` och [`TextSegment`](../textsegment/) Skillnaderna mellan dem är mestadels kontextberoende. Låt oss överväga följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta osv.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Fysiskt sett är pdf-textens representation mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen fastställer i grunden att `TextFragment`-objektet tillhandahåller en enda logisk uppsättning operationer över fysiska [`TextSegment`](../textsegment/) objekt som representerar användarens fråga. I textsökningsscenariot är `TextFragment` den logiska representationen av texten "hello world", och samlingen av [`TextSegment`](../textsegment/) objekt representerar alla fysiska segment som konstruerar textobjektet "hello world". Så, `TextFragment` är nära den logiska textrepresentationen. Och [`TextSegment`](../textsegment/) är nära den fysiska textrepresentationen. Uppenbarligen kan varje [`TextSegment`](../textsegment/) objekt ha sitt eget teckensnitt, färg, positioneringsegenskaper. `TextFragment` tillhandahåller ett enkelt sätt att ändra text med dess egenskaper: ställa in teckensnitt, ställa in teckensnittsstorlek, ställa in teckensnitts färg osv. Under tiden är [`TextSegment`](../textsegment/) objekten tillgängliga och användare kan arbeta med [`TextSegment`](../textsegment/) objekten oberoende. Observera att ändring av TextFragment-egenskaper kan ändra den inre [`Segments`](./segments/) samlingen eftersom TextFragment är ett aggregatobjekt och det kan omorganisera interna segment eller slå samman dem till ett enda segment. Om ditt krav är att lämna den inre [`Segments`](./segments/) samlingen oförändrad, vänligen ändra de inre segmenten individuellt.

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter texten och dess teckensnitt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)