---
title: TextSegment
second_title: Aspose.PDF för .NET API Referens
description: Representerar segment av PDF-text.
type: docs
weight: 7210
url: /sv/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Representerar segment av PDF-text.

```csharp
public sealed class TextSegment
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Skapar TextSegment-objekt. |
| [TextSegment](textsegment#constructor_1)(string) | Skapar TextSegment-objekt. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Får textposition för text, representerad med[`TextSegment`](../textsegment) object. YIndent av positionsstrukturen representerar baslinjekoordinaten för textsegmentet. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Får samling av CharInfo-objekt som representerar information om tecken i textsegmentet. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Hämtar slutteckenindex för aktuellt segment i segmentet showtextoperator (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Hämtar eller ställer in segmentets hyperlänk (för pdf-generator). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Får textposition för text, representerad med[`TextSegment`](../textsegment) objekt. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Får rektangel av TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Hämtar startteckenindex för aktuellt segment i segmentet showtextoperator (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Hämtar eller sätterString textobjekt som[`TextSegment`](../textsegment) objekt representerar. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Hämtar eller ställer in textredigeringsalternativ. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Hämtar eller ställer in texttillstånd för texten som[`TextSegment`](../textsegment) objekt representerar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Kodar sträng som html. |

### Anmärkningar

Med några få ord,[`TextSegment`](../textsegment) föremål är barn till[`TextFragment`](../textfragment) objekt. I detaljer: Text i pdf-dokument iPdf representeras av två grundläggande objekt:[`TextFragment`](../textfragment) och[`TextSegment`](../textsegment) Skillnaderna mellan dem är mestadels kontextberoende. Låt oss överväga följande scenario. Användaren söker efter texten "hej världen" för att arbeta med den, ändra dess egenskaper, utseende etc. Fysiskt sett är pdf-textens representation mycket komplex. Texten "hej världen" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen slår i grunden fast att[`TextFragment`](../textfragment) object tillhandahåller en enda logisk operation satt över fysisk[`TextSegment`](../textsegment) objektuppsättning som representerar användarens fråga. I textsökningsscenario,[`TextFragment`](../textfragment) är logisk "hej världen" textrepresentation, och[`TextSegment`](../textsegment)objektsamling representerar alla fysiska segment som konstruerar "hej världen" textobjekt. Så,[`TextFragment`](../textfragment) är nära logisk textrepresentation. And[`TextSegment`](../textsegment) är nära fysisk textrepresentation. Uppenbarligen var och en[`TextSegment`](../textsegment) objektet kan ha sitt eget typsnitt, färg, positioneringsegenskaper. [`TextFragment`](../textfragment) ger ett enkelt sätt att ändra text med dess egenskaper: ställ in teckensnitt, ställ in teckenstorlek, ställ in teckensnittsfärg etc. Under tiden[`TextSegment`](../textsegment) objekt är tillgängliga och användare kan arbeta med[`TextSegment`](../textsegment) objekt oberoende.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek på texten med[`TextState`](./textstate) föremål för[`TextSegment`](../textsegment) objekt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra förgrundsfärgen för det första textsegmentet i den första textförekomsten
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ändra teckenstorlek för det första textsegmentet i den första textförekomsten
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* namnutrymme [Aspose.Pdf.Text](../../aspose.pdf.text)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
