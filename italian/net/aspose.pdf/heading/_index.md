---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Heading. Rappresenta un'intestazione
type: docs
weight: 5470
url: /it/net/aspose.pdf/heading/
---
## Classe Heading

Rappresenta un'intestazione.

```csharp
public sealed class Heading : TextFragment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Heading](heading/)(int) | Inizializza una nuova istanza della classe Cell. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con l'oggetto [`TextFragment`](../../aspose.pdf.text/textfragment/). L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Ottiene la pagina di destinazione. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Ottiene o imposta la nota finale del paragrafo. (solo per la generazione di pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Ottiene o imposta la nota a piè di pagina del paragrafo. (solo per la generazione di pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Ottiene l'oggetto modulo che contiene il TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del frammento di testo. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Imposta il collegamento ipertestuale del frammento |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Ottiene se l'intestazione deve essere numerata automaticamente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Ottiene se l'intestazione deve essere nella lista toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione di pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Ottiene il livello. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Ottiene la pagina che contiene il TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Ottiene o imposta la posizione del testo per il testo, rappresentato con l'oggetto [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Ottiene il rettangolo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con un testo più corto/lungo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Ottiene i segmenti di testo per il corrente [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Ottiene il numero di inizio dell'intestazione. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Ottiene o imposta lo stile. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Ottiene o imposta l'oggetto String di testo che l'oggetto [`TextFragment`](../../aspose.pdf.text/textfragment/) rappresenta. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Ottiene o imposta lo stato del testo per il testo che l'oggetto [`TextFragment`](../../aspose.pdf.text/textfragment/) rappresenta. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Ottiene la pagina che contiene questa intestazione. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Ottiene la Y superiore di queste intestazioni. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Ottiene o imposta l'etichetta utente. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del frammento di testo. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Ottiene o imposta il conteggio delle righe avvolte per questo paragrafo (solo per la generazione di pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clona l'intestazione. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clona l'intestazione con tutti i segmenti. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Ottiene i [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) che rappresentano la parte specificata del testo [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Vedi Anche

* classe [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)