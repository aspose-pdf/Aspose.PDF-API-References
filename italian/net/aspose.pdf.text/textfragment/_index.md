---
title: "Classe TextFragment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextFragment. Rappresenta un frammento di testo Pdf"
type: docs
weight: 11120
url: /it/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Rappresenta un frammento di testo Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Inizializza una nuova istanza dell'oggetto `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Crea l'oggetto `TextFragment` con un singolo oggetto [`TextSegment`](../textsegment/) al suo interno. Specifica la stringa di testo all'interno del segmento. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Inizializza una nuova istanza dell'oggetto `TextFragment` con posizioni [`TabStops`](../tabstops/) predefinite. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Crea l'oggetto `TextFragment` con un singolo oggetto [`TextSegment`](../textsegment/) al suo interno e posizioni [`TabStops`](../tabstops/) predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Ottiene la posizione del testo, rappresentata con l'oggetto `TextFragment`. Lo YIndent della struttura Position rappresenta la coordinata di base del frammento di testo. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Ottiene o imposta la nota di fine paragrafo (solo per la generazione di PDF). |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Ottiene o imposta la nota a piè di pagina del paragrafo (solo per la generazione di PDF). |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Ottiene l'oggetto form che contiene il TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del frammento di testo. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Imposta il collegamento ipertestuale del frammento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Ottiene la pagina che contiene il TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Ottiene o imposta la posizione del testo, rappresentata con l'oggetto `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Ottiene il rettangolo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una lunghezza più breve o più lunga. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Ottiene i segmenti di testo per l'attuale `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Ottiene o imposta l'oggetto stringa di testo che rappresenta l'oggetto `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Ottiene o imposta lo stato del testo per il testo che l'oggetto `TextFragment` rappresenta. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del frammento di testo. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Ottiene o imposta il conteggio delle righe di avvolgimento per questo paragrafo (solo per la generazione di PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clona il frammento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clona il frammento con tutti i segmenti. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Ottiene [`TextSegment`](../textsegment/)(s) che rappresentano la parte specificata del testo del `TextFragment`. |

## Osservazioni

In poche parole, l'oggetto `TextFragment` contiene un elenco di oggetti [`TextSegment`](../textsegment/). In dettaglio: il testo di un documento PDF in Pdf è rappresentato da due oggetti di base: `TextFragment` e [`TextSegment`](../textsegment/). Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo \"hello world\" per operare su di esso, modificarne le proprietà, visualizzarlo ecc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La rappresentazione fisica del testo PDF è molto complessa. Il testo \"hello world\" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce fondamentalmente che l'oggetto `TextFragment` fornisce un unico insieme di operazioni logiche sui oggetti fisici [`TextSegment`](../textsegment/) che rappresentano la query dell'utente. In uno scenario di ricerca testo, `TextFragment` è la rappresentazione logica del testo \"hello world\", e la collezione di oggetti [`TextSegment`](../textsegment/) rappresenta tutti i segmenti fisici che costituiscono l'oggetto testo \"hello world\". Quindi, `TextFragment` è vicino alla rappresentazione logica del testo. E [`TextSegment`](../textsegment/) è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto [`TextSegment`](../textsegment/) può avere il proprio carattere, colore e proprietà di posizionamento. `TextFragment` offre un modo semplice per modificare il testo con le sue proprietà: impostare il carattere, la dimensione, il colore, ecc. Nel frattempo gli oggetti [`TextSegment`](../textsegment/) sono accessibili e gli utenti possono operare su di essi in modo indipendente. Nota che la modifica delle proprietà di TextFragment può modificare la collezione interna di [`Segments`](./segments/) perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se il tuo requisito è mantenere invariata la collezione di [`Segments`](./segments/), modifica i segmenti interni singolarmente.

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il testo e il carattere della prima occorrenza del testo
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


