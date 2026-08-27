---
title: "Class TextFragmentState"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Text.TextFragmentState class. Rappresenta lo stato di testo di un frammento di testo"
type: docs
weight: 11150
url: /it/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Rappresenta lo stato di testo di un frammento di testo

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
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Imposta il colore di sfondo del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/). |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Ottiene o imposta la spaziatura dei caratteri del testo, rappresentata dall'oggetto [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del carattere. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del carattere. Il valore predefinito è Descender. Se il valore Descent del carattere è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri caratteri. In questo caso, è possibile selezionare CoordinateOrigin BaseLine per una migliore resa del testo. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Ottiene o imposta il flag che indica se il bordo del rettangolo di testo è disegnato. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Ottiene o imposta il carattere del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Ottiene o imposta la dimensione del carattere del testo, rappresentata dall'oggetto [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Imposta lo stile del carattere del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Ottiene o imposta il colore di primo piano del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generatore. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del testo. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Ottiene o imposta la scala orizzontale del testo, rappresentata dall'oggetto [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Ottiene o imposta l'invisibilità del testo. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Ottiene o imposta l'interlinea del testo. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Ottiene o imposta la modalità di rendering del testo. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Ottiene o imposta il barrato per il testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Ottiene o imposta le operazioni di tracciatura colore del rendering di [`TextFragment`](../textfragment/) (tracciare il testo, bordo del rettangolo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Ottiene o imposta il pedice del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/). |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Ottiene o imposta il apice del testo, rappresentato dall'oggetto [`TextFragment`](../textfragment/). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Ottiene le tabulazioni per il testo. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | È possibile inserire questo tag nel testo per dichiarare la tabulazione. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Ottiene o imposta la sottolineatura per il testo, rappresentata dall'oggetto [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Ottiene o imposta la spaziatura delle parole del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Applica le impostazioni da un altro textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Verifica se la stringa di input può essere posizionata all'interno del rettangolo definito. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Misura l'altezza del carattere. (2 metodi) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Misura la stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valore predefinito della tabulazione nelle larghezze del carattere spazio del font predefinito. |

## Osservazioni

Fornisce un modo per modificare le seguenti proprietà del testo: carattere ([`Font`](./font/) proprietà) dimensione del carattere ([`FontSize`](./fontsize/) proprietà) stile del carattere ([`FontStyle`](./fontstyle/) proprietà) colore di primo piano ([`ForegroundColor`](./foregroundcolor/) proprietà) colore di sfondo ([`BackgroundColor`](./backgroundcolor/) proprietà) Nota che la modifica delle proprietà `TextFragmentState` può cambiare la collezione interna di [`Segments`](../textfragment/segments/) perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se il tuo requisito è mantenere invariata la collezione di [`Segments`](../textfragment/segments/), modifica i segmenti interni individualmente.

## Esempi

L'esempio dimostra come modificare il colore del testo e la dimensione del carattere del testo con l'oggetto [`TextState`](../textstate/).

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il colore di primo piano della prima occorrenza di testo
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Modifica la dimensione del carattere della prima occorrenza di testo
absorber.TextFragments[1].TextState.FontSize = 15;

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


