---
title: TextParagraph
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta i paragrafi di testo come oggetti di testo multilinea.
type: docs
weight: 7150
url: /it/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Rappresenta i paragrafi di testo come oggetti di testo multilinea.

```csharp
public sealed class TextParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextParagraph](textparagraph)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent) { get; set; } | Ottiene o imposta il valore di rientro delle righe successive. Se impostato su un valore diverso da zero, presenta un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions) { get; set; } | Ottiene o imposta le opzioni di formattazione. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale per il testo all'interno dei parametri[`Rectangle`](./rectangle) . |
| [Justify](../../aspose.pdf.text/textparagraph/justify) { get; set; } | Ottiene o imposta il valore se il testo è giustificato. |
| [Margin](../../aspose.pdf.text/textparagraph/margin) { get; set; } | Ottiene o imposta il riempimento. |
| [Position](../../aspose.pdf.text/textparagraph/position) { get; set; } | Ottiene o imposta la posizione del paragrafo. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle) { get; set; } | Ottiene o imposta il rettangolo del paragrafo. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent) { get; set; } | Ottiene o imposta il valore di rientro delle righe successive. Se impostato su un valore diverso da zero, presenta un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle) { get; } | Ottiene il rettangolo del testo inserito nel paragrafo. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale per il testo all'interno dei parametri[`Rectangle`](./rectangle) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_3)(string) | Aggiunge riga di testo |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline)(TextFragment) | Aggiunge la riga di testo con i parametri dello stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_6)(string, float) | Aggiunge riga di testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_4)(string, TextState) | Aggiunge la riga di testo con i parametri dello stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_1)(TextFragment, TextState) | Aggiunge la riga di testo con i parametri dello stato del testo. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_5)(string, TextState, float) | Aggiunge riga di testo con parametri di stato del testo |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_2)(TextFragment, TextState, float) | Aggiunge riga di testo con parametri di stato del testo |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit)() | Inizia la modifica del TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit)() | Termina la modifica del TextParagraph. |

### Esempi

L'esempio mostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

//passa in rassegna i frammenti
TextParagraph paragraph = new TextParagraph();
           
//esegui il ciclo dei segmenti
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

//scorri i personaggi
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// stampa la posizione del carattere e le informazioni sul rettangolo
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// crea un paragrafo di testo
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// imposta il rettangolo del paragrafo
doc.Save(outFile);
```

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->