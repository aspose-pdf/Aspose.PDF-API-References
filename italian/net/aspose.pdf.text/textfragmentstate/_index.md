---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta lo stato del testo di un frammento di testo.
type: docs
weight: 10970
url: /it/net/aspose.pdf.text/textfragmentstate/
---
## Classe TextFragmentState

Rappresenta uno stato di testo di un frammento di testo.

```csharp
public sealed class TextFragmentState : TextState
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Inizializza una nuova istanza dell'oggetto `TextFragmentState` con l'oggetto [`TextFragment`](../textfragment/) specificato. Questa inizializzazione di `TextFragmentState` non è supportata. TextFragmentState è disponibile solo con la proprietà [`TextState`](../textfragment/textstate/). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Imposta il colore di sfondo del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Ottiene o imposta la spaziatura dei caratteri del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Ottiene o imposta l'origine delle coordinate del testo. Se l'origine delle coordinate è Descender, la coordinata Y del testo corrisponde al punto più basso del carattere. Se l'origine delle coordinate è BaseLine, la coordinata Y del testo corrisponde alla linea di base del carattere. Il valore predefinito è Descender. Se il valore di discesa del carattere è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri caratteri. In questo caso, può essere selezionata l'origine delle coordinate BaseLine per una migliore visualizzazione del testo. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Ottiene o imposta il flag per il bordo del rettangolo del testo disegnato. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Ottiene o imposta il carattere del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Ottiene o imposta la dimensione del carattere del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Imposta lo stile del carattere del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Ottiene o imposta il colore di primo piano del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generazione. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale per il testo. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Ottiene o imposta la scala orizzontale del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Ottiene o imposta l'invisibilità del testo. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Ottiene o imposta la spaziatura delle righe del testo. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Ottiene o imposta la modalità di rendering del testo. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Ottiene o imposta il barrato per il testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Ottiene o imposta il colore delle operazioni di tracciamento del rendering di [`TextFragment`](../textfragment/) (tracciare testo, bordo rettangolo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Ottiene o imposta il pedice del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Ottiene o imposta l'apice del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Ottiene i tabulati per il testo. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Ottiene o imposta la sottolineatura per il testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Ottiene o imposta la spaziatura delle parole del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Applica le impostazioni da un altro textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Controlla se la stringa di input può essere posizionata all'interno del rettangolo definito. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Misura l'altezza del carattere. (2 metodi) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Misura la stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valore predefinito della tabulazione nelle larghezze del carattere di spazio del carattere predefinito. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Puoi posizionare questo tag nel testo per dichiarare la tabulazione. |

## Osservazioni

Fornisce un modo per modificare le seguenti proprietà del testo: carattere ([`Font`](./font/) proprietà) dimensione del carattere ([`FontSize`](./fontsize/) proprietà) stile del carattere ([`FontStyle`](./fontstyle/) proprietà) colore di primo piano ([`ForegroundColor`](./foregroundcolor/) proprietà) colore di sfondo ([`BackgroundColor`](./backgroundcolor/) proprietà) Nota che la modifica delle proprietà di `TextFragmentState` può cambiare la collezione interna [`Segments`](../textfragment/segments/) perché TextFragment è un oggetto aggregato e può riordinare i segmenti interni o unirli in un singolo segmento. Se la tua esigenza è mantenere invariata la collezione [`Segments`](../textfragment/segments/), ti preghiamo di modificare i segmenti interni singolarmente.

## Esempi

L'esempio dimostra come cambiare il colore del testo e la dimensione del carattere del testo con l'oggetto [`TextState`](../textstate/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi Anche

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* classe [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)