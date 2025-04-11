---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragment. Rappresenta un frammento di testo Pdf
type: docs
weight: 10940
url: /it/net/aspose.pdf.text/textfragment/
---
## Classe TextFragment

Rappresenta un frammento di testo Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Inizializza una nuova istanza dell'oggetto `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Crea un oggetto `TextFragment` con un singolo oggetto [`TextSegment`](../textsegment/) all'interno. Specifica la stringa di testo all'interno del segmento. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Inizializza una nuova istanza dell'oggetto `TextFragment` con posizioni [`TabStops`](../tabstops/) predefinite. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Crea un oggetto `TextFragment` con un singolo oggetto [`TextSegment`](../textsegment/) all'interno e posizioni [`TabStops`](../tabstops/) predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con l'oggetto `TextFragment`. L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Ottiene o imposta la nota finale del paragrafo. (solo per la generazione di pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Ottiene o imposta la nota a piè di pagina del paragrafo. (solo per la generazione di pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Ottiene l'oggetto modulo che contiene il TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del frammento di testo. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Imposta il collegamento ipertestuale del frammento |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione di pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Ottiene la pagina che contiene il TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Ottiene o imposta la posizione del testo per il testo, rappresentato con l'oggetto `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Ottiene il rettangolo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con uno più corto/lungo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Ottiene i segmenti di testo per il corrente `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Ottiene o imposta l'oggetto stringa di testo che l'oggetto `TextFragment` rappresenta. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Ottiene o imposta lo stato del testo per il testo che l'oggetto `TextFragment` rappresenta. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del frammento di testo. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Ottiene o imposta il conteggio delle righe avvolte per questo paragrafo (solo per la generazione di pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. Lo ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clona il frammento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clona il frammento con tutti i segmenti. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Ottiene i [`TextSegment`](../textsegment/)(s) che rappresentano la parte specificata del testo `TextFragment`. |

## Osservazioni

In poche parole, l'oggetto `TextFragment` contiene un elenco di oggetti [`TextSegment`](../textsegment/). In dettaglio: Il testo del documento pdf in Pdf è rappresentato da due oggetti di base: `TextFragment` e [`TextSegment`](../textsegment/). Le differenze tra di loro sono per lo più dipendenti dal contesto. Consideriamo il seguente scenario. L'utente cerca il testo "hello world" per operare su di esso, modificarne le proprietà, visualizzarlo, ecc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La rappresentazione fisica del testo pdf è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce fondamentalmente che l'oggetto `TextFragment` fornisce un insieme di operazioni logiche su un insieme di oggetti fisici [`TextSegment`](../textsegment/) che rappresentano la query dell'utente. Nello scenario di ricerca del testo, `TextFragment` è la rappresentazione logica del testo "hello world", e la collezione di oggetti [`TextSegment`](../textsegment/) rappresenta tutti i segmenti fisici che costruiscono l'oggetto di testo "hello world". Quindi, `TextFragment` è vicino alla rappresentazione logica del testo. E [`TextSegment`](../textsegment/) è vicino alla rappresentazione fisica del testo. Ovviamente, ogni oggetto [`TextSegment`](../textsegment/) può avere il proprio carattere, colore, proprietà di posizionamento. `TextFragment` fornisce un modo semplice per cambiare il testo con le sue proprietà: impostare il carattere, impostare la dimensione del carattere, impostare il colore del carattere, ecc. Nel frattempo, gli oggetti [`TextSegment`](../textsegment/) sono accessibili e gli utenti possono operare con gli oggetti [`TextSegment`](../textsegment/) in modo indipendente. Si noti che la modifica delle proprietà di TextFragment può cambiare la collezione interna [`Segments`](./segments/) perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un singolo segmento. Se la tua esigenza è mantenere la collezione [`Segments`](./segments/) invariata, si prega di modificare i segmenti interni individualmente.

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi Anche

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)