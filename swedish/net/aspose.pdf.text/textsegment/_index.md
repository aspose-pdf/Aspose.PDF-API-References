---
title: "Klass TextSegment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextSegment‑klass. Representerar ett segment av Pdf‑text."
type: docs
weight: 11240
url: /sv/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Representerar segment av Pdf-text.

```csharp
public sealed class TextSegment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Skapar TextSegment‑objekt. |
| [TextSegment](textsegment/#constructor_1)(string) | Skapar TextSegment‑objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med `TextSegment`‑objekt. YIndent‑värdet i Position‑strukturen representerar baslinjekoordinaten för textsegmentet. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Hämtar samling av CharInfo‑objekt som representerar information om tecken i textsegmentet. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Hämtar slutteckningsindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)‑segmentet. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Hämtar eller anger segmentets hyperlänk (för pdf‑generator). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Hämtar textposition för text, representerad med `TextSegment`‑objekt. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Hämtar rektangeln för TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Hämtar startteckningsindex för aktuellt segment i show‑text‑operatorn (Tj, TJ)‑segmentet. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Hämtar eller anger String‑textobjektet som `TextSegment`‑objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Hämtar eller anger texttillstånd för den text som `TextSegment`‑objektet representerar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Kodar sträng som html. |

## Anmärkningar

Med några ord är `TextSegment`‑objekt barn till [`TextFragment`](../textfragment/)‑objektet. I detalj: Texten i ett pdf‑dokument i Pdf representeras av två grundläggande objekt: [`TextFragment`](../textfragment/) och `TextSegment`. Skillnaderna mellan dem är mest kontextberoende. Låt oss överväga följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Den fysiska representationen av pdf-text är mycket komplex. Texten \"hello world\" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf-textmodellen fastställer i princip att [`TextFragment`](../textfragment/)‑objektet tillhandahåller en enda logisk operation uppsatt över fysiska `TextSegment`‑objekt som representerar användarens fråga. I textsökningsscenario är [`TextFragment`](../textfragment/) den logiska \"hello world\"-textrepresentationen, och samlingen av `TextSegment`‑objekt representerar alla fysiska segment som bygger upp \"hello world\"-textobjektet. Således är [`TextFragment`](../textfragment/) nära den logiska textrepresentationen. Och `TextSegment` är nära den fysiska textrepresentationen. Uppenbarligen kan varje `TextSegment`‑objekt ha sin egen teckensnitt, färgning och placeringsegenskaper. [`TextFragment`](../textfragment/) erbjuder ett enkelt sätt att ändra text med dess egenskaper: sätt teckensnitt, sätt teckensnittsstorlek, sätt teckensnittsfärg osv. Samtidigt är `TextSegment`‑objekt tillgängliga och användare kan arbeta med `TextSegment`‑objekt oberoende.

## Exempel

Exemplet visar hur man ändrar textfärg och teckensnittsstorlek för texten med [`TextState`](./textstate/)‑objektet för `TextSegment`‑objektet.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra förgrundsfärg för det första textsegmentet i den första textförekomsten
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ändra teckensnittsstorlek för det första textsegmentet i den första textförekomsten
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


