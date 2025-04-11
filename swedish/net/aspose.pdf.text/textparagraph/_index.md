---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph klass. Representerar textparagrafer som ett flerlinjigt textobjekt
type: docs
weight: 10990
url: /sv/net/aspose.pdf.text/textparagraph/
---
## TextParagraph klass

Representerar textparagrafer som ett flerlinjigt textobjekt.

```csharp
public sealed class TextParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextParagraph](textparagraph/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Hämtar eller sätter indenteringsvärdet för efterföljande rader. Om det sätts till ett icke-nollvärde har det en fördel över värdet FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Hämtar eller sätter formateringsalternativ. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Hämtar eller sätter horisontell justering för texten inuti paragrafens [`Rectangle`](./rectangle/). |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Hämtar eller sätter värdet om texten är rättjusterad. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Hämtar eller sätter marginalen. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Hämtar eller sätter positionen för paragrafen. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Hämtar eller sätter rektangeln för paragrafen. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Hämtar eller sätter rotationsvinkeln i grader. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Hämtar eller sätter indenteringsvärdet för efterföljande rader. Om det sätts till ett icke-nollvärde har det en fördel över värdet FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Hämtar rektangeln för texten placerad i paragrafen. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Hämtar eller sätter vertikal justering för texten inuti paragrafens [`Rectangle`](./rectangle/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Lägger till en textrad |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Lägger till en textrad med textstatusparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Lägger till en textrad. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Lägger till en textrad med textstatusparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Lägger till en textrad med textstatusparametrar. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Lägger till en textrad med textstatusparametrar |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Lägger till en textrad med textstatusparametrar |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Börjar redigera TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Avslutar redigeringen av TextParagraph. |

## Exempel

Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)