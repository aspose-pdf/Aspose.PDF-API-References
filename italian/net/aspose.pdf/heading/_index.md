---
title: Heading
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta lintestazione.
type: docs
weight: 3360
url: /it/net/aspose.pdf/heading/
---
## Heading class

Rappresenta l'intestazione.

```csharp
public sealed class Heading : TextFragment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Heading](heading)(int) | Inizializza una nuova istanza della classe Cell. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con[`TextFragment`](../../aspose.pdf.text/textfragment) oggetto. Il YIndent della struttura Posizione rappresenta la coordinata della linea di base del frammento di testo. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Ottiene la pagina di destinazione. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Ottiene o imposta la nota finale del paragrafo.(solo per la generazione di pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Ottiene o imposta la nota a piè di pagina del paragrafo.(solo per la generazione di pdf) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Ottiene l'oggetto modulo che contiene TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Ottiene o imposta un allineamento orizzontale del frammento di testo. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Imposta il collegamento ipertestuale del frammento |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Ottiene l'intestazione deve essere numerata automaticamente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Ottiene l'intestazione dovrebbe essere nell'elenco dei toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Ottiene il livello. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Ottiene la pagina che contiene TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Ottiene o imposta la posizione del testo per il testo, rappresentato con[`TextFragment`](../../aspose.pdf.text/textfragment) oggetto. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Ottiene il rettangolo di TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con più corto/lungo. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Ottiene i segmenti di testo per la corrente[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Ottiene il numero iniziale dell'intestazione. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Ottiene o imposta lo stile. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Ottiene o impostaString oggetto di testo che il[`TextFragment`](../../aspose.pdf.text/textfragment) l'oggetto rappresenta. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Ottiene o imposta lo stato del testo per il testo che[`TextFragment`](../../aspose.pdf.text/textfragment) l'oggetto rappresenta. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Ottiene la pagina che contiene questa intestazione. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Ottiene la Y superiore di queste intestazioni. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Ottiene o imposta l'etichetta utente. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del frammento di testo. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Ottiene o imposta il conteggio delle righe di avvolgimento per questo paragrafo (solo per la generazione di pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Clona l'intestazione. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Clona l'intestazione con tutti i segmenti. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Ottiene[`TextSegment`](../../aspose.pdf.text/textsegment) (s) che rappresenta una parte specificata del[`TextFragment`](../../aspose.pdf.text/textfragment) testo. |

### Guarda anche

* class [TextFragment](../../aspose.pdf.text/textfragment)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
