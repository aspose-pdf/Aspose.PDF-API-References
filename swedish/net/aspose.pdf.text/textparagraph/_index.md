---
title: "Klass TextParagraph"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextParagraph‑klass. Representerar textparagrafer som ett flerradigt textobjekt"
type: docs
weight: 11170
url: /sv/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Representerar textstycken som ett flerradigt textobjekt.

```csharp
public sealed class TextParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextParagraph](textparagraph/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Hämtar eller anger indragsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Hämtar eller anger formateringsalternativ. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering för texten i paragrafens [`Rectangle`](./rectangle/). |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Hämtar eller anger värde för om texten är justerad. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Hämtar eller anger utfyllnaden. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Hämtar eller anger positionen för paragrafen. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Hämtar eller anger rektangeln för paragrafen. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Hämtar eller anger rotationsvinkeln i grader. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Hämtar eller anger indragsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Hämtar rektangeln för texten placerad i paragrafen. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för texten i paragrafens [`Rectangle`](./rectangle/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Lägger till textrad |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Lägger till textrad med texttillståndsparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Lägger till textrad. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Lägger till textrad med texttillståndsparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Lägger till textrad med texttillståndsparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Lägger till textrad med texttillståndsparametrar |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Lägger till textrad med texttillståndsparametrar |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Påbörjar redigeringen av TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Avslutar redigeringen av TextParagraph. |

## Exempel

Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// skapa textparagraf
TextParagraph paragraph = new TextParagraph();
           
// ange paragrafens rektangel
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// ange alternativ för radbrytning
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// lägg till strängrader
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// lägg till paragrafen på Pdf-sidan med TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// spara Pdf-dokument
doc.Save(outFile);
```

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


