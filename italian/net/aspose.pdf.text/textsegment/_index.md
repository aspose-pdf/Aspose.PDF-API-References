---
title: "Classe TextSegment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextSegment. Rappresenta un segmento di testo Pdf"
type: docs
weight: 11240
url: /it/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Rappresenta un segmento di testo Pdf

```csharp
public sealed class TextSegment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Crea l'oggetto TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Crea l'oggetto TextSegment. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Ottiene la posizione del testo, rappresentata con l'oggetto `TextSegment`. L'YIndent della struttura Position rappresenta la coordinata di base del segmento di testo. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Ottiene la collezione di oggetti CharInfo che rappresentano le informazioni sui caratteri nel segmento di testo. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Ottiene l'indice del carattere finale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Ottiene la posizione del testo, rappresentata con l'oggetto `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Ottiene il rettangolo del TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Ottiene l'indice del carattere iniziale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Ottiene o imposta l'oggetto String di testo che l'oggetto `TextSegment` rappresenta. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Ottiene o imposta lo stato del testo per il testo che l'oggetto `TextSegment` rappresenta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Codifica la stringa come html. |

## Osservazioni

In poche parole, gli oggetti `TextSegment` sono figli dell'oggetto [`TextFragment`](../textfragment/). In dettaglio: il testo di un documento pdf in Pdf è rappresentato da due oggetti di base: [`TextFragment`](../textfragment/) e `TextSegment`. Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo "hello world" per operare su di esso, modificarne le proprietà, visualizzarlo, ecc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La rappresentazione fisica del testo pdf è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce fondamentalmente che l'oggetto [`TextFragment`](../textfragment/) fornisce un unico set di operazioni logiche sui set di oggetti `TextSegment` fisici che rappresentano la query dell'utente. Nello scenario di ricerca del testo, [`TextFragment`](../textfragment/) è la rappresentazione logica del testo "hello world", e la collezione di oggetti `TextSegment` rappresenta tutti i segmenti fisici che costituiscono l'oggetto testo "hello world". Quindi, [`TextFragment`](../textfragment/) è vicino alla rappresentazione logica del testo. E `TextSegment` è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto `TextSegment` può avere il proprio font, colore e proprietà di posizionamento. [`TextFragment`](../textfragment/) fornisce un modo semplice per modificare il testo con le sue proprietà: impostare il font, la dimensione del font, il colore del font, ecc. Nel frattempo gli oggetti `TextSegment` sono accessibili e gli utenti possono operare con gli oggetti `TextSegment` in modo indipendente.

## Esempi

L'esempio dimostra come modificare il colore del testo e la dimensione del font del testo con l'oggetto [`TextState`](./textstate/) del `TextSegment`.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Cambia il colore di primo piano del primo segmento di testo della prima occorrenza di testo
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Cambia la dimensione del font del primo segmento di testo della prima occorrenza di testo
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


