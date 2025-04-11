---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph-Klasse. Stellt Textabsätze als mehrzeiliges Textobjekt dar
type: docs
weight: 10990
url: /de/net/aspose.pdf.text/textparagraph/
---
## TextParagraph-Klasse

Stellt Textabsätze als mehrzeiliges Textobjekt dar.

```csharp
public sealed class TextParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextParagraph](textparagraph/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Ruft den Einzugswert für nachfolgende Zeilen ab oder legt ihn fest. Wenn auf einen Wert ungleich null gesetzt, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Ruft die Formatierungsoptionen ab oder legt sie fest. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung für den Text innerhalb des Absatzes [`Rectangle`](./rectangle/) ab oder legt sie fest. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Ruft den Wert ab oder legt ihn fest, ob der Text gerechtfertigt ist. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Ruft die Polsterung ab oder legt sie fest. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Ruft die Position des Absatzes ab oder legt sie fest. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Ruft das Rechteck des Absatzes ab oder legt es fest. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Ruft den Rotationswinkel in Grad ab oder legt ihn fest. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Ruft den Einzugswert für nachfolgende Zeilen ab oder legt ihn fest. Wenn auf einen Wert ungleich null gesetzt, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Ruft das Rechteck des Textes ab, das im Absatz platziert ist. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung für den Text innerhalb des Absatzes [`Rectangle`](./rectangle/) ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Fügt eine Textzeile hinzu |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Fügt eine Textzeile mit Textstatusparametern hinzu. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Fügt eine Textzeile hinzu. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Fügt eine Textzeile mit Textstatusparametern hinzu. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Fügt eine Textzeile mit Textstatusparametern hinzu. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Fügt eine Textzeile mit Textstatusparametern hinzu |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Fügt eine Textzeile mit Textstatusparametern hinzu |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Beginnt die Bearbeitung des TextParagraphs. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Beendet die Bearbeitung des TextParagraphs. |

## Beispiele

Das Beispiel zeigt, wie man ein Textabsatzobjekt erstellt und es zur Pdf-Seite hinzufügt.

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

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)