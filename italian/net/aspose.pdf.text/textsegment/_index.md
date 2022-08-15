---
title: TextSegment
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta il segmento del testo Pdf.
type: docs
weight: 7210
url: /it/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Rappresenta il segmento del testo Pdf.

```csharp
public sealed class TextSegment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Crea oggetto TextSegment. |
| [TextSegment](textsegment#constructor_1)(string) | Crea oggetto TextSegment. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con[`TextSegment`](../textsegment) oggetto. Il YIndent della struttura Posizione rappresenta la coordinata della linea di base del segmento di testo. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Ottiene la raccolta di oggetti CharInfo che rappresentano informazioni sui caratteri nel segmento di testo. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Ottiene l'indice del carattere finale del segmento corrente nel segmento Mostra operatore di testo (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore di pdf). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Ottiene la posizione del testo per il testo, rappresentato con[`TextSegment`](../textsegment) oggetto. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Ottiene il rettangolo del TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Ottiene l'indice del carattere iniziale del segmento corrente nel segmento Mostra operatore di testo (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Ottiene o impostaString oggetto di testo che il[`TextSegment`](../textsegment) l'oggetto rappresenta. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Ottiene o imposta lo stato del testo per il testo che[`TextSegment`](../textsegment) l'oggetto rappresenta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Codifica la stringa come html. |

### Osservazioni

In poche parole,[`TextSegment`](../textsegment) gli oggetti sono figli di[`TextFragment`](../textfragment) oggetto. In dettaglio: Testo del documento pdf inPdf è rappresentato da due oggetti fondamentali:[`TextFragment`](../textfragment) e[`TextSegment`](../textsegment) Le differenze tra loro dipendono principalmente dal contesto. Consideriamo il seguente scenario. L'utente cerca il testo "ciao mondo" per operare con esso, cambiarne le proprietà, guardare ecc. La rappresentazione fisica del testo pdf è molto complessa. Il testo "ciao mondo" può essere costituito da diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce sostanzialmente che[`TextFragment`](../textfragment) object fornisce un'operazione logica singola impostata su fisica[`TextSegment`](../textsegment) set di oggetti che rappresentano la query dell'utente. Nello scenario di ricerca di testo,[`TextFragment`](../textfragment) è la rappresentazione logica del testo "ciao mondo", e[`TextSegment`](../textsegment)la raccolta di oggetti rappresenta tutti i segmenti fisici che costruiscono l'oggetto di testo "hello world". Quindi,[`TextFragment`](../textfragment) è vicino alla rappresentazione logica del testo. E[`TextSegment`](../textsegment) è vicino alla rappresentazione fisica del testo. Ovviamente ciascuno[`TextSegment`](../textsegment) l'oggetto può avere il proprio carattere, colorazione, proprietà di posizionamento. [`TextFragment`](../textfragment) fornisce un modo semplice per modificare il testo con le sue proprietà: imposta il carattere, imposta la dimensione del carattere, imposta il colore del carattere ecc. Nel frattempo[`TextSegment`](../textsegment) gli oggetti sono accessibili e gli utenti sono in grado di operare[`TextSegment`](../textsegment) oggetti in modo indipendente.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Esempi

L'esempio mostra come modificare il colore del testo e la dimensione del carattere del testo con[`TextState`](./textstate) oggetto di[`TextSegment`](../textsegment) oggetto.

```csharp
// Modifica la dimensione del carattere della prima occorrenza del testo
Document doc = new Document(@"D:\Tests\input.pdf");

// Cambia il colore di primo piano della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Modifica la dimensione del carattere della prima occorrenza del testo
doc.Pages[1].Accept(absorber);

// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world".
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Apri documento
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world".
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
