---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph classe. Rappresenta i paragrafi di testo come oggetto di testo a righe multiple
type: docs
weight: 10990
url: /it/net/aspose.pdf.text/textparagraph/
---
## Classe TextParagraph

Rappresenta paragrafi di testo come oggetto di testo multilinea.

```csharp
public sealed class TextParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextParagraph](textparagraph/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Ottiene o imposta il valore di rientro delle linee successive. Se impostato su un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Ottiene o imposta le opzioni di formattazione. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale per il testo all'interno del [`Rectangle`](./rectangle/) della paragrafo. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Ottiene o imposta il valore se il testo è giustificato. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Ottiene o imposta il padding. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Ottiene o imposta la posizione del paragrafo. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Ottiene o imposta il rettangolo del paragrafo. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Ottiene o imposta il valore di rientro delle linee successive. Se impostato su un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Ottiene il rettangolo del testo posizionato nel paragrafo. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale per il testo all'interno del [`Rectangle`](./rectangle/) della paragrafo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Aggiunge una riga di testo |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Aggiunge una riga di testo con i parametri di stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Aggiunge una riga di testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Aggiunge una riga di testo con i parametri di stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Aggiunge una riga di testo con i parametri di stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Aggiunge una riga di testo con i parametri di stato del testo |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Aggiunge una riga di testo con i parametri di stato del testo |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Inizia la modifica del TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Termina la modifica del TextParagraph. |

## Esempi

L'esempio dimostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf.

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

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)