---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment klass. Representerar segment av Pdf-text
type: docs
weight: 11050
url: /sv/net/aspose.pdf.text/textsegment/
---
## TextSegment klass

Representerar segment av Pdf-text.

```csharp
public sealed class TextSegment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Skapar TextSegment-objekt. |
| [TextSegment](textsegment/#constructor_1)(string) | Skapar TextSegment-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med `TextSegment`-objekt. YIndent i Position-strukturen representerar baslinjekoordinaten för textsegmentet. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Hämtar samling av CharInfo-objekt som representerar information om tecken i textsegmentet. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Hämtar slutteckenindex för nuvarande segment i show text-operatorn (Tj, TJ) segment. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Hämtar eller ställer in segmentets hyperlänk (för pdf-generator). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Hämtar textposition för text, representerad med `TextSegment`-objekt. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Hämtar rektangeln för TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Hämtar startteckenindex för nuvarande segment i show text-operatorn (Tj, TJ) segment. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Hämtar eller ställer in String textobjekt som `TextSegment`-objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Hämtar eller ställer in textredigeringsalternativ. Alternativen definierar speciellt beteende när begärt symbol inte kan skrivas med typsnitt. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Hämtar eller ställer in textstatus för den text som `TextSegment`-objektet representerar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Kodar sträng som html. |

## Kommentarer

Med några få ord är `TextSegment`-objekt barn till [`TextFragment`](../textfragment/) objekt. I detalj: Texten i pdf-dokumentet i Pdf representeras av två grundläggande objekt: [`TextFragment`](../textfragment/) och `TextSegment`. Skillnaderna mellan dem är mestadels kontextberoende. Låt oss överväga följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta osv.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Den fysiska representationen av pdf-text är mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment. Aspose.Pdf textmodell fastställer i grunden att [`TextFragment`](../textfragment/) objektet tillhandahåller en enda logisk uppsättning operationer över den fysiska uppsättningen av `TextSegment`-objekt som representerar användarens fråga. I textsökningsscenariot är [`TextFragment`](../textfragment/) den logiska representationen av texten "hello world", och samlingen av `TextSegment`-objekt representerar alla fysiska segment som konstruerar textobjektet "hello world". Så, [`TextFragment`](../textfragment/) ligger nära den logiska textrepresentationen. Och `TextSegment` ligger nära den fysiska textrepresentationen. Uppenbarligen kan varje `TextSegment`-objekt ha sitt eget typsnitt, färg, positioneringsegenskaper. [`TextFragment`](../textfragment/) tillhandahåller ett enkelt sätt att ändra text med dess egenskaper: ställa in typsnitt, ställa in typsnittsstorlek, ställa in typsnittsfärg osv. Under tiden är `TextSegment`-objekt tillgängliga och användare kan arbeta med `TextSegment`-objekt oberoende.

## Exempel

Exemplet visar hur man ändrar textfärg och typsnittsstorlek för texten med [`TextState`](./textstate/) objektet av `TextSegment`-objekt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)