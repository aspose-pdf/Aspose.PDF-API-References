---
title: TextFragment
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un frammento di testo Pdf.
type: docs
weight: 7100
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
| [TextFragment](textfragment#constructor)() | Inizializza la nuova istanza di[`TextFragment`](../textfragment) oggetto. |
| [TextFragment](textfragment#constructor_2)(string) | Crea[`TextFragment`](../textfragment) oggetto con singolo[`TextSegment`](../textsegment) oggetto all'interno. Specifica la stringa di testo all'interno del segmento. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Inizializza la nuova istanza di[`TextFragment`](../textfragment) oggetto con predefinito[`TabStops`](../tabstops) posizioni. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Crea[`TextFragment`](../textfragment) oggetto con singolo[`TextSegment`](../textsegment) oggetto all'interno e predefinito[`TabStops`](../tabstops) posizioni. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con[`TextFragment`](../textfragment) oggetto. Il YIndent della struttura Posizione rappresenta la coordinata della linea di base del frammento di testo. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Ottiene o imposta la nota finale del paragrafo.(solo per la generazione di pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Ottiene o imposta la nota a piè di pagina del paragrafo.(solo per la generazione di pdf) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Ottiene l'oggetto modulo che contiene TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Ottiene o imposta un allineamento orizzontale del frammento di testo. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Imposta il collegamento ipertestuale del frammento |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Ottiene la pagina che contiene TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Ottiene o imposta la posizione del testo per il testo, rappresentato con[`TextFragment`](../textfragment) oggetto. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Ottiene il rettangolo di TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con più corto/lungo. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Ottiene i segmenti di testo per la corrente[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Ottiene o impostaString oggetto di testo che il[`TextFragment`](../textfragment) l'oggetto rappresenta. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Ottiene o imposta lo stato del testo per il testo che[`TextFragment`](../textfragment) l'oggetto rappresenta. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del frammento di testo. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Ottiene o imposta il conteggio delle righe di avvolgimento per questo paragrafo (solo per la generazione di pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Clona il frammento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Clona il frammento con tutti i segmenti. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Ottiene[`TextSegment`](../textsegment) (s) che rappresenta una parte specificata del[`TextFragment`](../textfragment) testo. |

### Osservazioni

In poche parole,[`TextFragment`](../textfragment) l'oggetto contiene un elenco di[`TextSegment`](../textsegment) oggetti. In dettaglio: Testo del documento pdf inPdf è rappresentato da due oggetti fondamentali:[`TextFragment`](../textfragment) e[`TextSegment`](../textsegment) Le differenze tra loro dipendono principalmente dal contesto. Consideriamo il seguente scenario. L'utente cerca il testo "ciao mondo" per operare con esso, cambiarne le proprietà, guardare ecc. La rappresentazione fisica del testo pdf è molto complessa. Il testo "ciao mondo" può essere costituito da diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce sostanzialmente che[`TextFragment`](../textfragment) object fornisce un'operazione logica singola impostata su fisica[`TextSegment`](../textsegment) set di oggetti che rappresentano la query dell'utente. Nello scenario di ricerca di testo,[`TextFragment`](../textfragment) è la rappresentazione logica del testo "ciao mondo", e[`TextSegment`](../textsegment)la raccolta di oggetti rappresenta tutti i segmenti fisici che costruiscono l'oggetto di testo "hello world". Quindi,[`TextFragment`](../textfragment) è vicino alla rappresentazione logica del testo. E[`TextSegment`](../textsegment) è vicino alla rappresentazione fisica del testo. Ovviamente ciascuno[`TextSegment`](../textsegment) l'oggetto può avere il proprio carattere, colorazione, proprietà di posizionamento. [`TextFragment`](../textfragment) fornisce un modo semplice per modificare il testo con le sue proprietà: imposta il carattere, imposta la dimensione del carattere, imposta il colore del carattere ecc. Nel frattempo[`TextSegment`](../textsegment) gli oggetti sono accessibili e gli utenti sono in grado di operare[`TextSegment`](../textsegment) oggetti in modo indipendente. Nota che la modifica delle proprietà di TextFragment può cambiare[`Segments`](./segments) raccolta perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un singolo segmento. Se il tuo requisito è lasciare il[`Segments`](./segments)raccolta invariata, cambia i segmenti interni individualmente.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// aggiungi un altro segmento alla raccolta Segments del frammento di testo
Document doc = new Document(@"D:\Tests\input.pdf");

// crea un oggetto TextBuilder
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// aggiunge il frammento di testo alla pagina Pdf
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

//salva documento
doc.Pages[1].Accept(absorber);

// Apri documento
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
