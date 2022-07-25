---
title: TextFragmentState
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta uno stato di testo di un frammento di testo.
type: docs
weight: 7130
url: /it/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Rappresenta uno stato di testo di un frammento di testo.

```csharp
public sealed class TextFragmentState : TextState
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Inizializza la nuova istanza di[`TextFragmentState`](../textfragmentstate) oggetto con specificato[`TextFragment`](../textfragment) oggetto. Questo[`TextFragmentState`](../textfragmentstate) l'inizializzazione non è supportata. TextFragmentState è disponibile solo con[`TextState`](../textfragment/textstate) proprietà. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Imposta il colore di sfondo del testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Ottiene o imposta la spaziatura dei caratteri del testo, rappresentata da[`TextFragment`](../textfragment) oggetto. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Ottiene o imposta se flag disegnato bordo rettangolo di testo. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Ottiene o imposta il carattere del testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Ottiene o imposta la dimensione del carattere del testo, rappresentata da[`TextFragment`](../textfragment) oggetto |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Imposta lo stile del carattere del testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Ottiene o imposta il colore di primo piano del testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà effettiva solo negli scenari del generatore. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale per il testo. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Ottiene o imposta il ridimensionamento orizzontale del testo, rappresentato da[`TextFragment`](../textfragment) oggetto. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Ottiene o imposta l'invisibilità del testo. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Ottiene o imposta l'interlinea del testo. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Ottiene o imposta la modalità di rendering del testo. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Ottiene o imposta l'angolo di rotazione in gradi. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Imposta la barratura per il testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Ottiene o imposta le operazioni di tracciatura del colore di[`TextFragment`](../textfragment) rendering (testo tratto, bordo rettangolo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Ottiene o imposta il pedice del testo, rappresentato da[`TextFragment`](../textfragment) oggetto. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Ottiene o imposta l'apice del testo, rappresentato da[`TextFragment`](../textfragment) oggetto. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Ottiene le tabulazioni per il testo. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Ottiene o imposta la sottolineatura per il testo, rappresentato da[`TextFragment`](../textfragment) oggetto |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Ottiene o imposta la spaziatura delle parole del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Applica le impostazioni da un altro textState. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Misura la stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Valore predefinito della tabulazione in larghezze di spazio carattere del carattere predefinito. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Puoi inserire questo tag nel testo per dichiarare la tabulazione. |

### Osservazioni

Fornisce un modo per modificare le seguenti proprietà del testo: font ([`Font`](./font) proprietà) dimensione del carattere ([`FontSize`](./fontsize) proprietà) stile carattere ([`FontStyle`](./fontstyle) proprietà) colore di primo piano ([`ForegroundColor`](./foregroundcolor) proprietà) colore di sfondo ([`BackgroundColor`](./backgroundcolor) proprietà) Si noti che la modifica[`TextFragmentState`](../textfragmentstate) le proprietà possono cambiare internamente[`Segments`](../textfragment/segments) raccolta perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un singolo segmento. Se il tuo requisito è lasciare il[`Segments`](../textfragment/segments) raccolta invariata, cambia i segmenti interni individualmente.

### Esempi

L'esempio mostra come modificare il colore del testo e la dimensione del carattere del testo con[`TextState`](../textstate) oggetto.

```csharp
// Modifica il testo della prima occorrenza del testo
Document doc = new Document(@"D:\Tests\input.pdf");

// Modifica il testo della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Modifica il testo della prima occorrenza del testo
doc.Pages[1].Accept(absorber);

// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world".
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Apri documento
absorber.TextFragments[1].TextState.FontSize = 15;

// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world".
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
