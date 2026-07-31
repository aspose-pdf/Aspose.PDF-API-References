---
title: "Classe TextParagraph"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextParagraph. Rappresenta i paragrafi di testo come oggetto di testo multilinea."
type: docs
weight: 11170
url: /it/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Rappresenta i paragrafi di testo come oggetto di testo multilinea

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
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Ottiene o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Ottiene o imposta le opzioni di formattazione. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del testo all'interno del [`Rectangle`](./rectangle/) del paragrafo. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Ottiene o imposta il valore che indica se il testo è giustificato. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Ottiene o imposta il padding. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Ottiene o imposta la posizione del paragrafo. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Ottiene o imposta Rectangle del paragrafo. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Ottiene o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Ottiene il Rectangle del testo posizionato nel paragrafo. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del testo all'interno del [`Rectangle`](./rectangle/) del paragrafo. |

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

L'esempio dimostra come creare un oggetto TextParagraph e aggiungerlo alla pagina Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// crea TextParagraph
TextParagraph paragraph = new TextParagraph();
           
// imposta il rettangolo del paragrafo
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// imposta le opzioni di a capo automatico
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// aggiungi righe di stringa
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// aggiungi il paragrafo alla pagina Pdf con il TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// salva il documento Pdf
doc.Save(outFile);
```

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


